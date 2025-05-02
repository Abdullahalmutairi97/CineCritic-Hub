# 🎬 CineCritic Hub - Movie Review Platform

A full-stack web application for movie enthusiasts to discover, review, and discuss films with both casual viewers and professional critics.

## ✨ Features

- **Movie Discovery**
  - Browse by genre, release year, and ratings
  - Personalized recommendations
  - Trending movies dashboard

- **Review System**
  - 5-star rating with written reviews
  - Spoiler warnings and content flags
  - Like/dislike and comment on reviews

- **User Profiles**
  - Personal watchlists
  - Review history and statistics
  - Follow critics and friends

- **Critic Verification**
  - Professional critic badges
  - Featured reviews section
  - Credential verification system

## 🛠️ Tech Stack

**Frontend:**
- React.js with Hooks
- Redux for state management
- Material-UI + custom SCSS
- Axios for API calls

**Backend:**
- Node.js & Express
- MongoDB (Mongoose ODM)
- JWT Authentication
- Redis for caching

**DevOps:**
- Docker containerization
- GitHub Actions CI/CD
- AWS EC2 deployment
- NGINX reverse proxy


```python
cinecritic-hub/
├── client/               # Frontend React application
│   ├── public/           # Static assets
│   └── src/              # React components and pages
│       ├── components/   # Reusable UI components
│       ├── pages/        # Route-level components
│       ├── store/        # Redux configuration
│       └── styles/       # Global SCSS styles
│
├── server/               # Backend Express application
│   ├── config/           # Database and auth config
│   ├── controllers/      # Route controllers
│   ├── middleware/       # Custom middleware
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   └── utils/            # Helper functions
│
├── .github/              # GitHub workflows
└── docs/                 # Project documentation
```
