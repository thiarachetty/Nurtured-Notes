# Nurtured Notes

A cozy, earthy day planner web app blending a clean calendar, to-do list, mood tracker, and live weather widget — all styled with a sleek, modern, natural aesthetic.

---

## Features

- **Interactive Calendar**  
  View current month, highlight today, and mark important dates with notes. Add, edit, and delete important dates through a smooth modal interface. Data saved with `localStorage` for persistence.

- **To-Do List with Progress Bar**  
  Easily add tasks, mark them done, and watch your progress grow. Your to-dos are saved locally to keep you on track day after day.

- **Mood Tracker**  
  Express your feelings using emoji buttons, get uplifting daily tips, and have your mood saved for continuity.

- **Live Weather Widget**  
  Fetches your current local weather using browser geolocation and Open-Meteo API, displaying temperature and simple weather icons.

---

## Getting Started

### Setup

1. Clone or download the project.
2. Ensure the `style.css` file is correctly linked in your HTML.
3. Open `index.html` (or your main HTML file) in a modern browser.

### Weather API Notes

- The app uses Open-Meteo’s free API for weather data.
- Location permission is required for accurate weather info.
- Replace or customize the weather API fetch URL and keys as needed for production.

---

## Usage

- Click the **📅 Expand Calendar** button to manage your important dates.
- Add tasks in the **To-Do List** and check them off to track progress visually.
- Select your mood from the emoji choices and receive personalized tips.
- Weather updates automatically when the page loads.

---

## Technologies

- HTML5 and CSS3 with a natural, minimalistic design.
- Vanilla JavaScript for interactivity and local data storage.
- [Open-Meteo API](https://open-meteo.com/) for real-time weather updates.

---

## Customization

- Adjust colors and fonts by editing CSS variables in `style.css`.
- Clear or modify localStorage keys (`plannerImportantDates`, `plannerTodos`, `plannerMood`) to reset or customize saved data.
- Swap the weather API or styling to fit your branding.

---

## Accessibility & Responsiveness

- Responsive layout that adapts smoothly to mobile devices.
- Accessible buttons with aria labels and focus states.
- Emoji mood selector for an intuitive and friendly UI.
- Semantic markup for screen reader compatibility.

---

## License

Open source and free to use, adapt, and remix for your personal or commercial projects.

---

Made with 💚 and earth vibes by **TDogg** ✨

