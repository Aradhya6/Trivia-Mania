# 🧠 Trivia Mania

An interactive, browser-based quiz game that challenges your knowledge across a wide range of topics — from science and history to music, films, and more.

---

## 🎮 Overview

Trivia Mania is a full-featured web quiz application powered by the [Open Trivia Database (OpenTDB)](https://opentdb.com/) API. Players can customize their experience by choosing a category, difficulty, number of questions, and a per-question time limit before diving in. Results are tracked and displayed at the end of each session.

---

## ✨ Features

- **User Authentication** — Sign up and log in; your name is remembered across sessions via `localStorage`
- **Customizable Quiz Settings** — Pick your category, difficulty level, number of questions (5–50), and time per question (10–60 seconds)
- **18+ Question Categories** — General Knowledge, History, Science, Mathematics, Music, Films, Video Games, Geography, Politics, and more
- **Live Countdown Timer** — An animated progress bar counts down for each question
- **Score Screen** — Final score shown at the end with the option to restart
- **Hamburger Navigation Menu** — Sidebar with links to Trivia, Instructions, Profile, and Logout
- **Fun Facts** — A rotating fun fact is displayed on the homepage on every visit
- **Animated UI** — Slide-in, fade-in, and bounce animations throughout the app

---

## 📁 Project Structure

```
Trivia-Mania/
├── main.html          # Landing / login gateway
├── login.html         # Login page
├── singup.html        # Sign-up page
├── homepage.html      # Home dashboard (post-login)
├── index.html         # Quiz setup & game screen
├── index1.html        # Alternate quiz variant
├── instructions.html  # How-to-play page
├── profile.html       # User profile page
├── score.html         # Score results page
├── script.js          # Core quiz logic (API fetch, timer, scoring)
├── script1.js         # Supporting script
├── style.css          # Main stylesheet
└── style1.css         # Alternate/supplementary styles
```

---

## 🚀 Getting Started

No build tools or dependencies required — this is a pure HTML/CSS/JavaScript project.

### Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/Aradhya6/Trivia-Mania.git
   cd Trivia-Mania
   ```

2. **Open in your browser**

   Simply open `main.html` in any modern browser:

   ```bash
   open main.html
   # or double-click the file in your file explorer
   ```

> **Tip:** For the best experience, use a local server (e.g. VS Code Live Server) to avoid any browser restrictions on `localStorage` or fetch calls.

---

## 🕹️ How to Play

1. Open the app and sign up or log in
2. From the homepage, click **Get Started**
3. Configure your quiz:
   - Select a **category** (or choose "Any")
   - Choose a **difficulty** (Easy / Medium / Hard / Any)
   - Set the **number of questions** (5 to 50)
   - Pick a **time limit** per question (10 to 60 seconds)
4. Click **Start Quiz** and answer each question before the timer runs out
5. Submit your answer and move to the next question
6. View your final score at the end and restart if you'd like another round

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| HTML5 | Page structure and layout |
| CSS3 | Styling and animations |
| JavaScript (Vanilla) | Quiz logic, timer, API calls |
| [OpenTDB API](https://opentdb.com/api_config.php) | Question data source |
| Font Awesome 6 | Icons |
| localStorage | Session persistence (username) |

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please keep code changes focused and well-commented.

---

## 📄 License

This project is open source. Feel free to use, modify, and distribute it.

---

*Built with curiosity and caffeine by [Aradhya6](https://github.com/Aradhya6)*
