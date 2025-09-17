# Japanese Flashcard Generator

A simple web app that helps you generate **Japanese flashcards** (Kanji, Hiragana, Meaning) from an Excel file.  
Supports exporting **Anki-ready TXT** with multiple card formats and displaying **Kanji stroke order** for better learning.

👉 [**Try it here**]([YOUR_GITHUB_PAGES_LINK](https://trongnhan73.github.io/create-flashcard))  

---

## ✨ Features
- Import **Excel (.xlsx)** containing Kanji, Hiragana, and Meaning.
- Visualize **Kanji stroke order**, with larger stroke display (1/3 screen).
- Export to **TXT file** compatible with Anki.
- Generate **3 types of flashcards automatically**:
  1. Kanji → Hiragana *(tag: `kanji,hiragana`)*
  2. Kanji → Meaning *(tag: `kanji,nghia`)*
  3. Hiragana → Meaning *(tag: `hiragana,nghia`)*

---

## 📂 Example Excel Format

| Kanji | Hiragana | Meaning   |
|-------|----------|-----------|
| 日    | にち     | Day/Sun   |
| 学    | がく     | Study     |
| 水    | みず     | Water     |

---

## 🚀 How to Use
1. Open the web app 👉 [here](https://trongnhan73.github.io/create-flashcard).
2. Upload your Excel file (`.xlsx`) with the correct format (Kanji, Hiragana, Meaning).
3. Preview flashcards on the web.
4. Export as **TXT file** and import directly into **Anki**.
5. Start studying! 🎉

---

## 🛠 Development
This project is built with:
- **HTML, CSS, JavaScript**
- **XLSX.js** for Excel parsing
- **Custom export logic** for Anki TXT

---

## 📌 To Do
- [ ] Add sample Excel download link  
- [ ] Improve UI/UX for mobile   

---

## 📄 License
MIT License – free to use and modify.

---

👨‍💻 Created for Japanese learners who want to study smarter with flashcards.
