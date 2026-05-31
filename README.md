# 🌌 Phatmal.live (ဖတ်မယ်)

> **Premium Webnovel Translation Portal** for Epic Xianxia & Wuxia Sagas.

Welcome to the GitHub repository for **[phatmal.live](https://winyannainghtut.github.io/)**, a beautifully curated and highly professional landing hub hosting high-quality translations of legendary Chinese webnovels. We focus on bringing immersive, distraction-free reading experiences for masterpieces by legendary Xianxia authors **Er Gen** and **Wang Yu**.

---

## 📖 Table of Contents

1. [Featured Novels](#-featured-novels)
2. [Key Features](#-key-features)
3. [Technology & Aesthetics](#-technology--aesthetics)
4. [Project Directory Layout](#-project-directory-layout)
5. [Local Development](#-local-development)
6. [Deployment](#-deployment)
7. [Disclaimer & Copyright](#-disclaimer--copyright)

---

## 📚 Featured Novels

Our translation catalog features some of the most highly-rated novels in the entire Chinese online literature community:

### 1. [Renegade Immortal (仙逆)](/Renegade-immortal/)
- **Author:** Er Gen (耳根)
- **Genre:** Xianxia, Cultivation, Action, Dark Fantasy, Defiance
- **Status:** Active / Ongoing Translation
- **Overview:** Follow the legendary saga of **Wang Lin**, a mortal youth born with mediocre talents who defies the heavens, survives ruthless betrayals, and steps onto a path paved with blood and determination to become a supreme god who rules over his own destiny.

### 2. [Pursuit of the Truth (求魔 - POTT)](/pott/)
- **Author:** Er Gen (耳根)
- **Genre:** Xianxia, Tragedy, Psychological, Cultivation, Mystery
- **Status:** Completed
- **Overview:** Journey along with **Su Ming**, the last Berserker, as he awakens in a freezing mountain of ice and snow. Plagued by lost memories and surrounded by an illusionary reality, Su Ming embarks on a tragic, soul-stirring journey to seek the truth of his identity and tear down the chains of fate.

### 3. [A Record of a Mortal's Journey to Immortality (凡人修仙传 - RMJI)](/ARecordofaMortalJourneytoImmortality/)
- **Author:** Wang Yu (忘语)
- **Genre:** Xianxia, Cultivation, Pragmatic, Action, Adventure
- **Status:** Active / Ongoing Translation
- **Overview:** Follow the story of **Han Li**, a highly cautious and ordinary village boy who joins a minor sect by chance. Lacking inherent talent, Han Li must rely on his razor-sharp wits, extreme vigilance, and a mysterious green vial that matures spiritual herbs to survive a brutal, cutthroat cultivation world and step onto the path of immortality.

---

## ✨ Key Features

- **Xianxia-Inspired Dark Aesthetics:** The portal is designed with a premium, custom dark-fantasy palette (obsidian, royal purples, and deep gold accents) to match the atmospheric themes of the novels.
- **Dynamic Search & Filtering:** Instant, client-side searching and filtering of novels using HTML5 data attributes and optimized JS.
- **Reading Progress Tracker:** Built-in interactive widget utilizing `localStorage` to persist your reading progress across sessions.
- **Responsive Layout:** Tailored with mobile-first CSS Grid and Flexbox grids, ensuring stunning visual displays across mobile, tablet, and desktop screens.
- **Quotes Carousel:** A curated carousel showcasing defining, epic quotes from the main characters of the novels (Wang Lin, Su Ming, and Han Li) to keep readers inspired.

---

## 🛠️ Technology & Aesthetics

- **Core Structure:** HTML5
- **Aesthetic Styling:** Vanilla CSS3 featuring custom properties (variables), modern glassmorphism backdrops, responsive grid designs, custom webkit scrollbars, and fine-tuned hover animations.
- **Typography:** Premium Google Fonts:
  - `Cinzel` for majestic headers and titles.
  - `Inter` for ultra-clean, highly readable UI text and novel descriptions.
- **Icons:** [FontAwesome 6.4.0](https://fontawesome.com/)
- **Interactive Scripting:** Lightweight, zero-dependency Vanilla ES6+ JavaScript.

---

## 📁 Project Directory Layout

```text
winyannainghtut.github.io/
│
├── index.html                  # Main entrance & premium portal hub
├── README.md                   # Repository documentation (this file)
│
├── assets/                     # Shared static assets
│   └── images/                 # Custom cover artwork and background assets
│       ├── hero_bg.png         # Majestic high-fantasy hero background
│       ├── renegade_immortal.png # Wang Lin character art & novel cover
│       ├── pursuit_of_the_truth.png # Su Ming character art & novel cover
│       └── mortal_journey.png  # Han Li character art & novel cover
│
├── Renegade-immortal/          # Chapter files and directory for Renegade Immortal
├── pott/                       # Chapter files and directory for Pursuit of the Truth
└── ARecordofaMortalJourneytoImmortality/ # Chapter files and directory for Mortal's Journey
```

---

## 💻 Local Development

To run the portal locally and test modifications:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/winyannainghtut/winyannainghtut.github.io.git
   cd winyannainghtut.github.io
   ```

2. **Serve the project:**
   Since the project uses absolute-relative links (`/Renegade-immortal/`, `/pott/`), it is best served via a local web server (rather than opening the raw HTML file from disk). You can launch a quick server using any of the following:

   - **Using VS Code Live Server extension:** Click "Go Live" in the bottom-right corner.
   - **Using Python:**
     ```bash
     python -m http.server 8000
     ```
     Then navigate to `http://localhost:8000`.
   - **Using Node.js (`http-server`):**
     ```bash
     npx http-server -p 8000
     ```

---

## 🚀 Deployment

The site is configured to deploy instantly using **GitHub Pages**. 
Any changes committed and pushed to the `main` branch will be compiled and made live automatically at **[winyannainghtut.github.io](https://winyannainghtut.github.io/)** (mapped to the custom domain `phatmal.live`).

---

## ⚖️ Disclaimer & Copyright

1. **Translations:** All translations hosted on this site are fan-made creations intended for non-commercial, standard reading and educational purposes.
2. **Copyright:** The original raw text, lore, characters, and storylines of *Renegade Immortal (仙逆)*, *Pursuit of the Truth (求魔)*, and *A Record of a Mortal's Journey to Immortality (凡人修仙传)* belong entirely to the authors **Er Gen (耳根)** and **Wang Yu (忘语)**, and the respective publishing platforms (Qidian). 
3. **Images:** Cover illustrations are custom-generated digital fantasy artworks created solely to visualize the epic realms of the stories.

---

*“If heaven wants to block me, I will shatter heaven. If the earth wants to bury me, I will crush the earth!”* — **Wang Lin**
