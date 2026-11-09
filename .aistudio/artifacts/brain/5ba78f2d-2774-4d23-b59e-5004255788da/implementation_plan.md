# Noor: Complete UI Design Specification & Architecture

A definitive, all-in-one Islamic spiritual, educational, and lifestyle companion application delivering every single signature feature, utility, and reference found in **Islam360** and **Muslim Pro**. Noor unifies location-based astronomical prayer times with neighborhood mosque Azan/Iqamah schedules, a multi-mode **Qibla Direction Suite (Magnetic Compass, Great Circle Map View, Solar Shadow Method & Sensor Calibration)**, a full-featured **Mosque Locator with facilities and navigation**, deep live **Quran.com API v4** integration (search, word-by-word, tafsir, multi-reciter audio), complete **Sunnah.com canonical Hadith explorer** (Kutub al-Sittah, book-by-book chapters, scholar grading), a **Khatam Quran Completion Goal Tracker**, **Makkah & Madinah 24/7 Live Streams**, a **Global Du'a Community Request Wall (Ameen Counter)**, **Customizable Adhan Voices**, **Qalbox Curated Islamic Media**, a **Daily Sunnah & Lifestyle Feed**, the **40 Rabbana Duas from the Quran**, a **Thematic Quran Subject Index (Mawzoo'i Quran)**, **Protective Verses (Ayat-ul-Kursi, 4 Quls, Manzil)**, a **Hijri-Gregorian Date Converter & Lunar Calendar**, a **Halal Food Finder**, **Daily Devotionals & Duas**, a **Community Q&A Forum** with verified scholar badges, an **Islamic Will (Wasiyyah) Guide**, a **Zakat Calculator**, an **Islamic Inheritance (Miras/Faraid) Calculator**, a **Daily Salah & Qada Tracker**, **Asma ul Husna & Asma un Nabi (ﷺ)**, the **Six Kalimas of Islam**, a **Step-by-Step Wudu & Namaz Guide**, a **Ramadan Sehri/Iftar Hub**, a **Hajj & Umrah Step-by-Step Guide**, a **Halal Food & E-Numbers Checker**, an **Islamic Baby Names Dictionary**, an **Islamic Quote Card Maker**, curated **Audio Bayans & Lectures**, an interactive **Islamic Knowledge Quiz**, **Stories of the Prophets (Qisas al-Anbiya)**, and a **Tajweed & Quran Learning (Noorani Qaida)** academy.

---

## User Review & Critical Decisions

> [!IMPORTANT]
> Below is the complete, high-fidelity UI layout and interaction design that will be implemented:

- **Screen 1: Top Navigation Bar & Atmospheric Header**:
  - Live city name with GPS indicator and manual city search popup.
  - Dual Hijri and Gregorian date display (e.g. *27 Jumada al-Awwal 1448 / Nov 9, 2026*).
  - Quick-action buttons: Mosque Settings, Notification Bell (Adhan settings), and the **"Islamic Hub"** Grid button.
- **Screen 2: Core 5-Tab Material 3 Navigation**:
  - **Tab 1 (Prayers / Today)**: Atmospheric Hero Countdown Card with animated sky gradient, live ticking clock to next prayer, 6 prayer timetable cards (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha) with mosque Azan & Iqamah indicators, Adhan audio preview, and quick shortcuts.
  - **Tab 2 (Quran Reader - Quran.com v4)**: Surah directory (114 Surahs with Arabic calligraphy, translation, revelation type), Ayah reader with Uthmani text, translation, word-by-word modal, and floating bottom audio reciter bar (Mishary Alafasy, AbdulBaset, Sudais).
  - **Tab 3 (Hadith Explorer - Sunnah.com)**: Collection tabs (Bukhari, Muslim, 40 Nawawi), book-by-book chapter browser, authentic Hadith cards with Arabic text, translation, narrator, and verified scholar grade badges.
  - **Tab 4 (Devotionals & Duas)**: Daily rotating Dua of the Day card with spiritual benefits, 40 Rabbana Duas carousel, categorized Hisn al-Muslim supplications library, and Room bookmarks.
  - **Tab 5 (Community & Du'a Wall)**: Dual-view: (a) Scholar Q&A forum with verified scholar answer cards in gold containers, and (b) Global Du'a Request Wall where users submit prayers and tap "Ameen" with real-time counters.
- **Screen 3: Islamic Hub Suite (Interactive Sheet / Drawer)**:
  - 1-Tap categorized access to all specialized utilities:
    1. *Multi-Mode Qibla Suite* (360° Compass, Geodesic Map, Solar Shadow, Calibration)
    2. *Mosque Locator & Direction Launcher*
    3. *Daily Salah & Qada Tracker* (Prayer streaks and make-up counter)
    4. *Zakat Calculator* (Gold/Silver Nisab thresholds & 2.5% computation)
    5. *Islamic Inheritance (Miras / Faraid) Calculator*
    6. *Ramadan Sehri & Iftar Hub* (Live Suhoor/Iftar countdowns & Ashra Duas)
    7. *Makkah & Madinah 24/7 Live Stream Player*
    8. *Qalbox Halal Islamic Media & Documentaries Showcase*
    9. *Khatam Quran 30-Day Completion Tracker*
    10. *Digital Tasbeeh Counter with Haptics*
    11. *99 Names of Allah & Prophet Muhammad ﷺ*
    12. *Tajweed & Noorani Qaida Academy*
    13. *Stories of the Prophets (Qisas al-Anbiya)*
    14. *Six Kalimas of Islam*
    15. *Step-by-Step Wudu & Namaz Illustrated Guide*
    16. *Halal Food & E-Numbers Ingredient Checker*
    17. *Islamic Baby Names Dictionary*
    18. *Islamic Will (Wasiyyah) Guide*
    19. *Hijri Date Converter*
    20. *Islamic Quote Card Maker*
    21. *Curated Audio Bayans & Lectures*
    22. *Interactive Islamic Knowledge Quiz*
    23. *Daily Sunnah Lifestyle Feed*

---

## 1. Overview & Core Concept

- **What It Does**: Noor is the complete, definitive Android Islamic ecosystem. It supports all five pillars of Islamic practice and knowledge: Salah (with GPS prayer times, Mosque custom Azan/Iqamah, multi-mode Qibla suite, Salah tracker & Qada ledger), Sawm (Ramadan Sehri/Iftar calendar & fasting Duas), Zakat (dynamic multi-asset wealth calculator), Hajj (step-by-Step interactive ritual guide), Shahadah (Six Kalimas and authentic Aqeedah), Quran (Quran.com live API, word-by-word roots, tafsir, 40 Rabbana Duas, Mawzoo'i thematic index, multi-reciters), Sunnah (Sunnah.com canonical Hadiths), Fiqh/Miras (Inheritance calculator, Halal food checker, Wasiyyah guide), and Community (scholar-verified Q&A, global Du'a wall).
- **Target Audience / Persona**: Muslims seeking an all-in-one, ad-free, battery-efficient, spiritually elevating companion app that honors Islamic tradition with state-of-the-art Android design.
- **Key Value**: Every Islamic necessity under one roof, with instant offline responsiveness, authentic citations, and modern Material 3 design.

---

## 2. User Experience & Visual Design

### Visual Identity & Theme
- **Color Palette**:
  - `Primary / Imperial Emerald`: `#0A382C` (Deep Islamic green, spiritual tranquility)
  - `Secondary / Sand Gold`: `#C5A059` & `#D4AF37` (Metallic gold for scholar badges, active prayer cards, and compass needle)
  - `Surface Parchment`: `#F9FAF7` (Crisp readability for long Arabic and English scriptures)
  - `Surface Night Emerald`: `#07211A` (Atmospheric dark theme)
  - `Scholar Illuminated Accent`: `#F4E8C1` (Soft golden highlight for verified scholar answers)
- **Typography**:
  - Quranic & Hadith Arabic: Large Uthmani Arabic script (32–36sp) with vowel diacritics.
  - English Scripture & Articles: High-legibility serif and sans pairing for contemplative devotionals and lessons.
  - Numbers & Counters: Bold tabular figures for prayer countdowns, Tasbeeh counts, streaks, and Zakat calculations.

---

## 3. Key Product Decisions & Trade-Offs

- **Decision 1: Modular Multi-Screen Jetpack Compose Architecture**
  - Clean separation between core daily screens (Prayer, Quran, Hadith, Duas, Community) and the extended Hub tools (Qibla, Zakat, Mosque Locator, Salah Tracker, Makkah Live, etc.) with BackHandler integration.
- **Decision 2: 100% Offline Resilience**
  - Essential astronomical calculations, Qibla math, Room database entities, and reference libraries run entirely offline with zero network required, while Quran.com and Sunnah.com APIs stream extended content when connected.

---

## 4. Technical Architecture & Component Mapping

```
┌────────────────────────────────────────────────────────────────────────┐
│                              MainActivity                              │
│       ┌────────────────────────────────────────────────────────┐       │
│       │               Scaffold & BottomNavigation               │       │
│       │  [Prayers]   [Quran]   [Hadith]   [Devotionals]  [Community]   │
│       └──────────────────────────┬─────────────────────────────┘       │
│                                  │                                     │
│   ┌──────────────┬───────────────┼───────────────┬─────────────────┐   │
│   ▼              ▼               ▼               ▼                 ▼   │
│[PrayerTab]  [QuranTab]      [HadithTab]    [DevotionalTab]   [CommunityTab]
│- Hero Clock - Quran.com v4  - Sunnah.com   - Daily Dua Rot.  - Q&A Forum
│- Azan/Iqamah- Sahih Int'l   - Topic Filter - 40 Rabbana Duas - Du'a Wall
│- Timetable  - Multi-Reciter - Narrator Tag - Thematic Quran  - Scholar Badge
│- Countdown  - Khatam Tracker- Commentary   - Daily Sunnah    - Ameen Counter
│- Mosque Loc - Word-by-Word  - Sunnah Links - Bookmarks       - Upvotes
│   │              │               │               │                 │   │
│   └──────────────┼───────────────┴───────────────┼─────────────────┘   │
│                  ▼                               ▼                     │
│         [Qibla Direction Suite]        [Education, Media & Tools]      │
│         - 360° Magnetic Compass Dial   - Qalbox Halal Media Showcase   │
│         - Great Circle Map Mode        - Six Kalimas of Islam          │
│         - Solar & Shadow Angle Method  - Wudu & Namaz Illustrated Guide│
│         - Sensor Calibration Guide     - Inheritance (Faraid) Calc     │
│         - Distance & Azimuth Telemetry - Islamic Will (Wasiyyah) Guide │
│                                        - Hajj & Umrah Ritual Guide     │
│         [Mosque & Location Engine]     - Halal Food & E-Numbers Checker│
│         - Nearby Mosque Directory      - Islamic Baby Names Dictionary │
│         - Facilities (Women, Wudu)     - Islamic Quote Card Maker      │
│         - Navigation Intent Launcher   - Tajweed & Noorani Qaida       │
│         - Ramadan Sehri/Iftar Hub      - Stories of the Prophets       │
│         - Salah & Qada Tracker         - Islamic Knowledge Quiz        │
│         - Zakat Calculator             - Curated Audio Bayans          │
│         - 99 Names of Allah & Prophet                                  │
│                  │                               │                     │
│                  └───────────────┬───────────────┘                     │
│                                  ▼                                     │
│                     ┌────────────────────────┐                         │
│                     │    Repository Layer    │                         │
│                     └────────────┬───────────┘                         │
│                                  │                                     │
│         ┌────────────────────────┴────────────────────────┐            │
│         ▼                                                 ▼            │
│  [Network / APIs]                                 [Room Database]      │
│  - Quran.com v4 API                               - PrayerLogDao       │
│  - Sunnah.com API                                 - QadaLedgerDao      │
│  - Audio Recitation / Bayan CDNs                  - QuranBookmarkDao   │
│  - Makkah / Madinah Live Streams                  - KhatamProgressDao  │
│                                                   - MosqueTimingDao    │
│                                                   - DuaBookmarkDao     │
│                                                   - CommunityForumDao  │
│                                                   - DuaWallRequestDao  │
│                                                   - ZakatRecordDao     │
└────────────────────────────────────────────────────────────────────────┘
```
