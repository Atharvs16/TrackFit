# 🏋️ Personalized Fitness Goal Tracker

A simple yet powerful web app that helps users set, track, and visualize their fitness and wellness goals. Built with **React.js**, **Tailwind CSS**, and optional animations using **Framer Motion**, this app is fully responsive and designed to motivate users to achieve their personal milestones.

---

## ✨ Features

- ✅ **Add custom fitness goals** (e.g., "Run 5 km", "Do 50 push-ups", "Yoga for 30 days")
- 📊 **Track progress** and update goal completion status
- 💾 **Local data persistence** using LocalStorage (keeps data even after refresh)
- ⚡ **Progress visualization** with simple progress bars or charts
- 🎉 **Gamified feedback** (celebrations on goal completion)
- 📱 Fully responsive and mobile-friendly UI

---

## 🛠️ Tech Stack

- **Frontend:** React.js (with hooks)
- **Styling:** Tailwind CSS
- **State Management:** React Context or simple useState/useReducer
- **Persistence:** LocalStorage
- **Animations (Optional):** Framer Motion

---

## 💡 Pages & Components

### Pages

- `/` — Home page showing current goals and progress
- `/add-goal` — Page to add a new goal
- `/goal/:id` — Detailed page for each goal (progress updates)

### Components

- Navbar
- Goal Card (displays each goal)
- Progress Bar or Circle
- Add Goal Form
- Celebration Modal or Animation

---

## ⚙️ Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/fitness-goal-tracker.git

# Navigate into the directory
cd fitness-goal-tracker

# Install dependencies
npm install

# Start the app locally
npm start
