# Jeju Innovation Growth Center — Bilingual Carousel (한·영)

A 10-slide bilingual (Korean + English) HTML/CSS carousel introducing the **Jeju Innovation Growth Center**. Every slide displays both Korean and English simultaneously, designed for international audiences who may have some familiarity with Korean.

---

## Preview

| Slide | Korean | English |
|---|---|---|
| 1 | 제주에서 창업하면 달라집니다 | Starting up in Jeju changes everything |
| 2 | 제주에 ICT 창업 허브가 생겼다 | Jeju now has an ICT startup hub |
| 3 | 아이디어가 공간 앞에서 멈춘다 | Great ideas get stuck on logistics |
| 4 | 센터는 단순한 임대 공간이 아니다 | This is more than just a rented space |
| 5 | 창업에 필요한 모든 공간이 여기 | Every space a founder needs, here |
| 6 | 장비도, 예약도 다 갖춰져 있다 | Equipment & booking fully covered |
| 7 | 입주와 예약, 4단계면 된다 | Move in or book, 4 simple steps |
| 8 | 창업의 성패는 환경이 절반이다 | A startup's success is half environment |
| 9 | 지금 당장 확인할 것 | Check these right now |
| 10 | 제주에서의 시작을 고민 중이라면 | Thinking about starting up in Jeju? |

---

## Files

```
soojin-carousel-bilingual/
├── jeju-innovation-center-bilingual.html   # Bilingual carousel (10 slides)
├── capture-slides.cjs                      # PNG export script (Playwright)
└── slides/
    ├── 01-cover.png
    ├── 02-why-jeju.png
    ├── 03-problem.png
    ├── 04-what-is-it.png
    ├── 05-spaces.png
    ├── 06-support.png
    ├── 07-how-to.png
    ├── 08-insight.png
    ├── 09-checklist.png
    └── 10-cta.png
```

---

## Design

- **Format**: 540 × 675 px per slide → exported at **1080 × 1350 px** (2x, Instagram-ready)
- **Typography**:
  - Korean: `Noto Sans KR` — headings & body
  - English: `Inter` — sub-labels & translations (muted opacity)
- **Layout**: Korean text is primary (larger, full opacity) · English sits beneath as secondary (smaller, ~40–60% opacity)
- **Color palette**:
  - Ocean Blue `#0B4F6C`
  - Jeju Teal `#00B4CC`
  - Accent Orange `#FF6B35`
  - Dark `#0D1B2A`
- **Images**: Official facility photos from [jeju-sp.com](https://www.jeju-sp.com/english/innovation/facility/starter.htm) (used with permission)

---

## Usage

**Preview in browser**
Open `jeju-innovation-center-bilingual.html` directly — no build step required.

**Export PNG slides**
```bash
npm install
node capture-slides.cjs
```
PNG files are saved to `slides/`. Re-run anytime after editing the HTML.

---

## Related

- [soojin-carousel](https://github.com/SunnySoojin/soojin-carousel) — English-only version

---

## About the Center

**Jeju Innovation Growth Center** (제주혁신성장센터) is an ICT startup convergence hub located inside the Jeju Advanced Science & Technology Complex.

- **Address**: 213-4 Cheomdan-ro, Jeju City · Semiyang Building, Block A, 2F
- **Phone**: 064-797-5500
- **Email**: jeju-sp@jdcenter.com
- **Hours**: Weekdays 9:00–18:00
- **Website**: [www.jeju-sp.com](https://www.jeju-sp.com)

### Facilities

| Space | Capacity | Notes |
|---|---|---|
| Private Offices 전용 오피스 | 20 units | Tenants only |
| Meeting Rooms 소회의실 | 8 people × 3 | Reservable online |
| Conference Rooms 컨퍼런스룸 | 19 people × 3 | Up to 3 months advance |
| Infinity Hall 인피니티홀 | 30–40 people | Projector & microphones included |
