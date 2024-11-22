<h1 align="center">Interactive Data Visualization Dashboard</h1>
<div align="center">
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=Chart.js&logoColor=white" alt="chart.js"/>
    <img src="https://img.shields.io/badge/reactrouter-CA4245?style=for-the-badge&logo=reactrouter&logoColor=black" alt="react-router"/>
    <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="vite" />
    <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" alt="nodejs"/>
<img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" alt="jwt"/>
<img src="https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb"/>
<img src="https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white" alt="express"/>
<img src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/>
<img src="https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD" alt="nodemon">
<img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="vercel">
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 📁 [Project Structure](#structure)
4. 🔋 [Features](#features)
5. 📍 [Important Note](#note)
6. 🤸 [Local Setup](#setup)

### <a name="introduction">🤖 Introduction</a>

An intuitive full-stack web application that enables users to visualize product analytics, manage user authentication, and share customized charts. Built using React, Node.js, and MongoDB, and deployed seamlessly with Vercel.

### <a name="tech-stack">⚙️ Tech Stack</a>

| **Category**   | **Technologies**              |
| -------------- | ----------------------------- |
| Frontend       | React, Tailwind CSS, Chart.js |
| Backend        | Node.js, Express.js, Mongoose |
| Database       | MongoDB Atlas                 |
| Deployment     | Vercel                        |
| Authentication | JWT, bcrypt                   |

### <a name="structure">📁 Project Structure</a>

### **Frontend Directory** (`/frontend`)

```
src/
├── components/            # Reusable UI components (charts, filters)
├── utils/                 # Helper functions for cookies
```

### **Backend Directory** (`/backend`)

```
├── controllers/           # Logic for handling API requests
├── models/                # Mongoose schemas
├── routes/                # API routes (auth, data, charts)
├── middlewares/           # Authentication and error-handling middlewares
```

### <a name="features">🔋 Features</a>

**Frontend Features 🌐**

1. User Interface:

   - Clean and responsive design with Tailwind CSS.
   - Optimized for desktop, tablet, and mobile devices.

2. Interactive Data Visualization:

   - Bar Chart: Displays total time spent on features for a selected date range.
   - Line Chart: Shows time trends with options to pan, zoom-in, and zoom-out.

3. Advanced Filtering Options:

   - Date Range Selector: Specify custom time ranges for analytics.
   - Filters by Age (15-25, >25) and Gender (Male, Female).
   - Charts update dynamically based on selected filters.

4. Chart Sharing:

   - Generate sharable links for specific charts with custom filters and date ranges.
   - Secured with authentication for data confidentiality.

5. User Authentication:

   - Signup, login, and logout functionalities.
   - Authenticated sessions managed via JWT.

6. Persistent Preferences:

   - Save user-selected filters and date ranges using cookies.
   - Option to reset or clear saved preferences.

<br/>

**Backend Features 💻**

1. Robust API:

   - JWT-based user authentication.
   - APIs for data retrieval, chart generation, and sharing.

2. MongoDB Integration:

   - Hosted on MongoDB Atlas for scalable and secure database management.
   - Mongoose for schema-based data modeling.

3. Error Handling:

   - Centralized error-handling middleware for efficient debugging.
   - Input validation to ensure data integrity.

4. CORS Configuration:

   - Allows requests only from trusted origins.

5. Scalability:
   - Deployed on Vercel for serverless and auto-scaling capabilities.

### <a name="note">📍 Important Note</a>

- This repository is a combination of both frontend and backend portions of the app.
- For proper implementation of each part you can go to the following links for better understanding of the app:
  1. Frontend Repository: [https://github.com/aditya-narayan-sahoo/moonshot-q2-frontend](https://github.com/aditya-narayan-sahoo/moonshot-q2-frontend)
  2. Backend Repository: [https://github.com/aditya-narayan-sahoo/moonshot-q2-backend](https://github.com/aditya-narayan-sahoo/moonshot-q2-backend)

### <a name="setup">🤸 Local Setup</a>

For the local setup you can refer to the steps given in the frontend and backend repository links given in the [Important Note Section](#note)
