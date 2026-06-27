# 📊 LeetMetric - LeetCode Profile Analyzer


LeetMetric is a responsive web application that allows users to analyze any public LeetCode profile by simply entering a username. It fetches real-time coding statistics using the LeetCode Stats API and displays problem-solving progress with animated circular progress indicators.

# ✨ Features

- 🔍 Search any public LeetCode username
- 📈 Displays solved Easy, Medium and Hard problems
- 📊 Circular progress indicators
- 🏆 Shows LeetCode Ranking
- ✅ Acceptance Rate
- 💯 Contribution Points
- ⚡ Real-time data using API
- ✔ Username validation
- 📱 Fully Responsive Design
- 🎨 Modern UI

---

# 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API
- LeetCode Stats API

---

# 📂 Project Structure

```
LeetMetric/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── preview.png
```

---

# ⚙️ How It Works

1. Enter a valid LeetCode username.
2. Click the **Search** button.
3. The application sends a request to the LeetCode Stats API.
4. The API returns the user's coding statistics.
5. The dashboard updates automatically with:

- Easy Problems Solved
- Medium Problems Solved
- Hard Problems Solved
- Acceptance Rate
- Global Ranking
- Contribution Points

---

# 🌐 API Used

LeetCode Stats API

```
https://leetcode-stats-api.vercel.app/{username}
```

Example

```
https://leetcode-stats-api.vercel.app/codedthoughts
```

---

# 📋 Validation

The application validates usernames before sending requests.

✔ Empty usernames are not allowed.

✔ Supports letters

✔ Supports numbers

✔ Supports underscores (_)

✔ Supports hyphens (-)

✔ Maximum 15 characters

---

# 📱 Responsive Design

The application works on

- Desktop
- Laptop
- Tablet
- Mobile

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/LeetMetric.git
```

Move into the project

```bash
cd LeetMetric
```

Open

```
index.html
```

or use **VS Code Live Server**.

---

# 🎯 Future Improvements

- Dark / Light Theme
- User Profile Image
- Contest Rating
- Contest History
- Submission Calendar
- Heatmap
- Recent Submissions
- Charts using Chart.js
- Compare Two Users
- Save Search History
- Export Statistics as PDF

---

# 📚 What I Learned

Through this project I learned

- JavaScript Fetch API
- Async / Await
- Promises
- DOM Manipulation
- CSS Grid
- CSS Flexbox
- Circular Progress UI
- Form Validation
- API Integration
- Error Handling
- Responsive Design

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Ashir Raj**

🎓 B.Tech - Computer Science & Engineering (AI)

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- LeetCode
- LeetCode Stats API
- JavaScript Community