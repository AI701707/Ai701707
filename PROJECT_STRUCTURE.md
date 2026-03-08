# Project Structure Documentation

## Full Directory Structure
```
AI701707/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── utils/
│   └── services/
├── tests/
│   ├── integration/
│   ├── unit/
│   └── e2e/
├── public/
│   ├── images/
│   └── index.html
├── config/
├── scripts/
├── README.md
└── PROJECT_STRUCTURE.md
```

## Technology Stack
- **Frontend:** React.js, Redux
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Testing:** Jest, Cypress
- **Deployment:** Docker, AWS

## Module Breakdown
- **components:** Contains reusable UI components.
- **pages:** Contains route components for pages.
- **styles:** Global and component-specific styles.
- **utils:** Utility functions and helpers.
- **services:** API service functions for backend communication.

## Database Schema Overview
- **Users**: `{ id, name, email, password, role }`
- **Projects**: `{ id, title, description, userId, createdAt, updatedAt }`
- **Tasks**: `{ id, title, description, status, createdAt, updatedAt, projectId }`

## API Endpoints Overview
- **GET /api/users**: Get all users.
- **GET /api/projects**: Get all projects related to a user.
- **POST /api/projects**: Create a new project.
- **GET /api/tasks**: Get all tasks related to a project.
- **POST /api/tasks**: Create a new task in a project.

---
*Documentation generated on 2026-03-08 16:17:37 (UTC)*