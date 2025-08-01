# 🎂 Age Calculator

A simple, elegant **Age Calculator** web app built with **HTML, CSS, and JavaScript**.  
It takes your birth date and calculates your exact age in **years, months, and days** — all on the client side, no data stored. 🙌

> 🔗 **Live App:** [Click to Use](https://saivardhanmanikala.github.io/AgeCalculator/)  
> 🛠 **Repo:** [GitHub Link](https://github.com/saivardhanmanikala/AgeCalculator)


---

✨ Features

- 🧮 Calculate age from birthdate (in **years**, **months**, and **days**)
- 📆 Supports all valid dates (with basic validation)
- 💡 Instant result with no page reload
- 🎨 Clean and responsive UI with soft shadows
- 🛡 100% frontend-based – nothing stored or sent to a server

---

🛠 Tech Stack

| Part     | Tech       |
|----------|------------|
| Structure | HTML5      |
| Styling   | CSS3       |
| Logic     | JavaScript |
| Hosting  | GitHub Pages |

---

🚀 How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/saivardhanmanikala/AgeCalculator.git
cd AgeCalculator
````

2. **Open `index.html` in your browser**

No build tools, no server needed. Simple and fast 🚀

---

🧠 Logic Behind the Scenes

The app compares the **current date** to the **entered birthdate**, calculates the difference, and adjusts for negative months or days. Handles leap years and month rollover too.

```js
if (ageDays < 0) {
  ageMonths--;
  ageDays += daysInPreviousMonth;
}

if (ageMonths < 0) {
  ageYears--;
  ageMonths += 12;
}
```

---

📂 File Structure

```
AgeCalculator/
├── index.html      # Main UI and JS logic
├── README.md       # You’re reading this!
└── preview.png     # (optional) Screenshot for GitHub display
```

---

🙋 Author

**Sai Vardan Manikala**
Frontend Developer | Bapatla Engineering College
🌐 \[Portfolio Coming Soon]
🔗 [GitHub](https://github.com/saivardhanmanikala)

---

📜 License

This project is licensed under the [MIT License](LICENSE).
Free to use, fork, and improve — just give credit, bro ✌️

---

⭐ Show Some Love

If this helped you or you liked it:

* ⭐ Star the repo
* 🍴 Fork it and customize
* 🔁 Share it with friends

Let’s build cool stuff together! 🚀

```

✅ Want Additions?

- Dark mode toggle?  
- Animated transitions?  
- Add birthday countdown?  
Just say the word, and I’ll help you level this up! 🔥
```
