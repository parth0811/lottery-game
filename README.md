# 🎰 Lottery Game

A simple Lottery Game built using **React.js** where users can generate random lottery tickets and check whether they win based on predefined winning conditions.

## 🚀 Features

- Generate random lottery tickets
- Display ticket numbers dynamically
- Check winning conditions
- React component-based architecture
- Clean and responsive UI
- Reusable helper functions

---

## 📂 Project Structure

```bash
src/
│
├── App.jsx
├── App.css
│
├── Lottery.jsx
├── Lottery.css
│
├── Ticket.jsx
├── Ticket.css
│
├── TicketNum.jsx
├── TicketNum.css
│
├── helper.js
│
└── main.jsx
```

---

## 🛠️ Technologies Used

- React.js
- JavaScript (ES6+)
- CSS3
- Vite

---

## 🎮 How It Works

1. A lottery ticket containing random numbers is generated.
2. The application checks the ticket against a winning condition.
3. If the condition is satisfied, the user wins.

### Current Winning Condition

```javascript
sum(ticket) === 15
```

The sum of all ticket numbers must be equal to **15**.

Example:

```bash
Ticket: [5, 4, 6]
Sum = 15 ✅ Winner
```

---

## 📸 Screenshots

### Lottery Game UI

```md
![Lottery Game](./screenshots/lottery-game.png)
```

Create a folder named **screenshots** in the root directory and place your screenshot inside it.

Example:

```bash
screenshots/
└── lottery-game.png
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/lottery-game.git
```

Navigate to the project folder:

```bash
cd lottery-game
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open:

```bash
http://localhost:5173
```

---

## 📚 Learning Concepts Covered

- React Components
- Props
- State Management
- Event Handling
- Conditional Rendering
- Array Methods
- Component Styling

---

## 🔮 Future Improvements

- Multiple winning conditions
- Custom ticket size
- Scoreboard
- Winning history
- Sound effects
- Animations
- Difficulty levels

---

## 👨‍💻 Author

**Parth Girdhar**

- MERN Stack Developer
- React Enthusiast

LinkedIn:
https://www.linkedin.com/in/parth-girdhar0811/

---

## 📜 License

This project is open source and available under the MIT License.