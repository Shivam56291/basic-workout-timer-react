# 🏋️‍♂️ React Workout Timer

A **dynamic and intuitive workout timer** built with React. This application lets you plan and calculate the total duration of your workout based on the type of exercise, number of sets, speed, and break duration. It even adjusts workout options depending on the **time of day (AM/PM)**.

🌐 **Live Demo** → [Workout Timer on Netlify](https://app.netlify.com/projects/basic-workout-timer-reactpractice/configuration/general)

📂 **Source Code** → [GitHub Repository](https://github.com/Shivam56291/basic-workout-timer-react)

---

## ✨ Features

- **Dynamic Workout Plans**

  - Adjusts exercises automatically depending on **AM or PM**
  - Example: "Full-body workout" has 9 exercises in the morning, 8 in the evening

- **Customizable Sessions**

  - Choose type of workout (Full-body, Arms + Legs, Core, etc.)
  - Select number of sets (1–5)
  - Adjust exercise speed (30s – 180s per exercise)
  - Set break duration between sets (1–10 mins)

- **Real-time Duration Calculation**

  - Workout time updates instantly as you tweak inputs

- **Manual Adjustment**

  - Fine-tune workout duration with `+` and `–` buttons

- **Sound Effects**

  - Optional **click sound** when workout duration updates

- **Extras**
  - Live clock (`time updates every second`)
  - Dynamic page title (e.g., "Your 8-exercise workout")

---

## 🛠️ Tech Stack

- [React.js](https://reactjs.org/) – Components, hooks (`useState`, `useEffect`, `useMemo`)
- JavaScript (ES6+) – Core app logic
- HTML5 & CSS3 – Layout and styling
- [Netlify](https://www.netlify.com/) – Hosting

---

## 🚀 Getting Started

Follow these steps to set up the project locally:

### Prerequisites

Make sure you have **Node.js** (which includes npm) installed.

```bash
node -v
npm -v


Installation

Clone the repo

 - git clone https://github.com/Shivam56291/basic-workout-timer-react.git


Navigate into the project folder

- cd basic-workout-timer-react


Install dependencies

- npm install


Start the development server

- npm start


Your app will now be running at http://localhost:3000 . 🎉

📂 Project Structure
basic-workout-timer-react/
│
├── public/                # Static assets
├── src/
│   ├── App.js             # Main app component
│   ├── Calculator.js      # Workout logic + duration calculation
│   ├── ToggleSounds.js    # Sound toggle button
│   ├── ClickSound.m4a     # Sound effect
│   ├── index.js           # Entry point
│   └── index.css          # Styling
│
└── package.json
```
