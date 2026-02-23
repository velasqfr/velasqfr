# Hi there 👋, I'm Franklin Velasquez

**Full-Stack Software Engineer** | JavaScript (ES6+), React, Node.js, MongoDB | Background in Accounting & Business Operations  
Bilingual: English & Spanish

I build **scalable, maintainable web applications** that solve real-world problems. With a foundation in business operations and accounting, I bring a unique perspective to software development—turning business requirements into practical software solutions.

📫 **Contact Me:** [Email](mailto:velasqfr96@gmail.com) | [LinkedIn](https://www.linkedin.com/in/franklin-velasquez-12ba4735a/) | [Portfolio](https://github.com/velasqfr)

---

## 🛠️ Skills

- **Languages & Frameworks:** JavaScript (ES6+), React.js, Node.js, Express.js, HTML5, CSS3
- **Databases:** MongoDB, NoSQL
- **Tools & Ecosystem:** Git, GitHub, JWT, REST APIs, Context API, Vite, Webpack, Babel
- **Developer Practices:** Responsive Design, ESLint, Prettier, Browser Persistence
- **Other:** QuickBooks, Payroll, Accounting, Bilingual (Spanish/English)

---

## 📂 Projects

| Project                                  | Description                                                                                                                                                          | Tech Stack                                                    | Live / How to Run                                                                                                                                                                              |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spots Classic** 🖼️                     | Social media web app for adding, liking, and deleting posts                                                                                                          | HTML, CSS, JS, CSS Grid, Figma                                | [View Live](https://velasqfr.github.io/se_project_spots_classic/)                                                                                                                              |
| **Spots JS** ⚡                          | Enhanced Spots with modular JS, Webpack, dynamic behavior                                                                                                            | HTML, CSS, JS (ES6 Modules), Webpack, Babel                   | [View Live](https://velasqfr.github.io/se_project_spots/) or run locally: `npm install` → `npm run dev` → open `localhost`                                                                     |
| **Triple Peaks Library** 📚              | Library webpage with events, staff picks, and membership steps                                                                                                       | HTML, CSS, Flexbox, Positioning                               | [View Live](https://velasqfr.github.io/se_project_library/)                                                                                                                                    |
| **Franky's Café Shop** ☕                | Responsive coffee shop webpage with menu, booking form, and animations                                                                                               | HTML, CSS, Flexbox, Form Validation, CSS Animations           | [View Live](https://velasqfr.github.io/se_project_coffeeshop/)                                                                                                                                 |
| **News Explorer** 📰                     | SPA fetching and displaying news articles dynamically via REST API                                                                                                   | React, JS, REST API, Vite                                     | [View Live](https://velasqfr.github.io/news_explorer/)                                                                                                                                         |
| **WTWR (Weather-Based Wardrobe App)** 🌤️ | Full-stack app giving personalized clothing recommendations based on weather. Users can register, log in, add, like, and delete clothing items, and manage profiles. | React (Vite), Node.js, Express, MongoDB, JWT, OpenWeather API | [Live React Demo](https://keen-clafoutis-fb8712.netlify.app/) / [Frontend Repo](https://github.com/velasqfr/se_project_react) / [Backend Repo](https://github.com/velasqfr/se_project_express) |

> ⚠️ Note: Static HTML/CSS projects can run live via GitHub Pages. JS module projects require building locally (npm run dev) or deploying via Netlify/Vercel. WTWR dynamic features require the backend repo to be running; frontend-only live demo displays the UI and static data.

---

## 📝 WTWR: Weather-Based Wardrobe App (React + Express)

WTWR is a full-stack weather web app that helps users pick clothing items suited to the current weather.

- Users can register, log in, add, like, and delete clothing items, and update profiles.
- Displays weather-based clothing recommendations with real-time weather info and temperature toggling (°F/°C).

### Features

- **Weather Integration**
  - Fetches real-time weather data using an external API
  - Displays location-based weather information
  - Supports temperature toggling between Fahrenheit (°F) and Celsius (°C)

- **Interactive Clothing Card System**
  - Displays clothing items filtered by weather type (Hot, Warm, Cold)
  - Clickable cards show a preview of item details

- **Modal System**
  - Preview modal for viewing item details
  - Add-item modal for uploading new garments
  - Authentication modals for registration and login
  - Edit profile modal for updating user info
  - Delete confirmation modal for item removal

- **User Features**
  - Secure user registration & login
  - Ability to add, like, and delete clothing item cards
  - Edit user profile (name & avatar)
  - Toggle between temperature units (°F/°C)

### ⚙️ Technologies and Techniques

- Frontend: React (Vite)
- Backend: Express.js (Node.js)
- Authentication: JWT-based secure login
- API Integration: OpenWeather API
- State Management: React Hooks + Context API
- Form Validation: Controlled components with inline validation
- Styling: Responsive CSS
- Developer Tools: Prettier, ESLint, Vite Dev Server

### 🔑 Backend API Overview

- **🛡️ Auth Endpoints**
  - `POST /signup` — Register new user
  - `POST /signin` — Log in
- **👤 User Endpoints**
  - `GET /users/me` — Get current user info
  - `PATCH /users/me` — Update profile info
- **🧥 Clothing Item Endpoints**
  - `GET /items` — Fetch all items
  - `POST /items` — Add new item
  - `DELETE /items/:itemId` — Delete item by ID
- **❤️ Like Endpoints**
  - `PUT /items/:itemId/likes` — Like an item
  - `DELETE /items/:itemId/likes` — Remove like

**Backend Repository:** [se_project_express](https://github.com/velasqfr/se_project_express)

---

### 💻 Installation & Running Locally

```bash
# Clone frontend repo
git clone https://github.com/velasqfr/se_project_react.git
cd se_project_react
npm install
npm run dev   # Start frontend dev server (Vite)

# Backend setup
cd ../se_project_express
npm install
npm start    # Start Express backend
```

⚠️ Tip: To run WTWR fully locally, start both frontend and backend. The frontend live demo displays the UI but requires the backend to enable login, add, and like features.
