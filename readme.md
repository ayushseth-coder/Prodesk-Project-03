# Dev-Detective – GitHub Profile Search Client (Sprint 03)

Dev-Detective is a **Vanilla JavaScript–based GitHub Profile Search Application**
built as part of **Sprint 03 Engineering Deliverables** at **Prodesk IT**.

This sprint focuses on **asynchronous JavaScript, API communication, promise handling,
error states, and dynamic DOM rendering**, without using any frontend frameworks.git

---

##  Sprint Objective

To build a **client-side application** that communicates with the **GitHub REST API**
and allows users to:

- Search GitHub users by username
- Fetch remote data using HTTP requests
- Render profile information dynamically
- Handle loading and error states gracefully
- Work with asynchronous JavaScript logic
- Compare two GitHub users using real API data

This sprint prepares the foundation for **React-based architecture in upcoming sprints**.

---

##  Technical Architecture

The application follows a clean and scalable frontend architecture:

1. **Search Layer** – User input handling & validation  
2. **Async Data Layer** – Fetch API with Async/Await  
3. **State Handling** – Loading, Success, and Error UI states  
4. **Render Layer** – Dynamic DOM updates based on API response  
5. **Utility Functions** – Date formatting, calculations, comparisons  

This structure ensures the application is **robust, readable, and easy to debug**.

---

##  Features Implemented

### Phase 1: Base MVP (Mandatory)
- GitHub username search input
- Profile card UI
- Fetch user data using GitHub REST API
- Render:
  - Avatar
  - Name
  - Bio
  - Join Date
  - Portfolio URL
- Loading indicator while data is fetching
- Clean error UI for **404 – User Not Found**

---

### Phase 2: Data Expansion (Priority)
- Fetch repositories using `repos_url`
- Display **Top 5 latest repositories**
- Clickable repository links (open in new tab)
- Human-readable date formatting from ISO timestamps

---

### Phase 3: Advanced Logic (Stretch Goals)
- Battle Mode with dual user input
- Parallel API calls using `Promise.all()`
- Calculate total repository stars using `reduce()`
- Conditional UI rendering:
  - Winner highlighted in green
  - Loser highlighted in red

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript (ES6)**
- **Fetch API**
- **GitHub REST API**

---

## ✅ Sprint Status

- Phase 1 (Mandatory): **Completed**
- Phase 2 (Priority): **Completed**
- Phase 3 (Stretch Goals): **Completed**

All Sprint 03 deliverables successfully implemented
using **Vanilla JavaScript and native browser APIs**.

---

## 🔗 Important Links

- GitHub: https://github.com/ayushseth-coder  
- LinkedIn: https://linkedin.com/in/ayush-seth-b4265828a  
- Live Demo: (add your deployed link here)  
- QA Video: (add your Loom video link here)  
- Web Screenshot:  
   [web screenshot](image.png)

---

## 👤 Author

**Ayush**  
Sprint 03 – Asynchronous Data & APIs  
Prodesk IT