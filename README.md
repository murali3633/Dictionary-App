# 📖 Dictionary App in JavaScript

A simple and interactive **English Dictionary App** built using **HTML, CSS, and JavaScript**.  
It uses the **Free Dictionary API** to fetch meanings, examples, pronunciations, and synonyms of words.
---

## 🚀 Features 
- 🔍 Search for any English word  
- 📖 Get **meaning** and **example sentence**  
- 🗣️ Listen to the word pronunciation with **audio support**  
- 📝 View a list of **synonyms** (clickable for instant search)  
- ❌ Clear search with one click  
- ⚡ Responsive and clean UI design  

---

## 🛠️ Tech Stack
- **HTML5** – Structure  
- **CSS3** – Styling & Responsive UI  
- **JavaScript (Vanilla JS)** – Functionality & API integration  
- **API:** [Free Dictionary API](https://dictionaryapi.dev/)  

---

## 📂 Project Structure
```
dictionary-app/
│── index.html       # Main HTML structure
│── style.css        # Styling (UI/UX)
│── script.js        # App logic & API handling
└── README.md        # Project documentation
```

---

## ⚙️ How It Works
1. User types a word in the search bar and presses **Enter**.  
2. App sends a request to:  
   ```
   https://api.dictionaryapi.dev/api/v2/entries/en/<word>
   ```
3. API returns JSON data containing word details.  
4. JavaScript processes the response and updates the UI:  
   - Word + pronunciation  
   - Meaning  
   - Example sentence  
   - Synonyms list  
5. User can click the **🔊 icon** to hear pronunciation or click a synonym to search it instantly.  

---

## 💻 Setup & Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/dictionary-app.git
   ```
2. Open the folder:  
   ```bash
   cd dictionary-app
   ```
3. Open `index.html` in your browser.  


