# CIT FindIt — Smart Campus Lost-and-Found Management System

A full-stack campus utility for students, faculty, and staff to report lost belongings, post found items, search listings, and manage safe item recovery at Chennai Institute of Technology (CIT).

## Planned stack

- **Frontend:** React + Vite
- **Backend:** Node.js + Express.js REST API
- **Database:** PostgreSQL
- **Authentication:** bcrypt password hashing and JWT
- **Uploads:** Multer for item photos

## Planned features

- Register and log in to the portal
- Create lost-item and found-item reports
- Browse, search, and filter reports by category, date, location, and keywords
- Submit ownership claims without exposing sensitive identifying details publicly
- Review claims and track an item's recovery status
- Suggest possible lost/found matches and notify users

## Repository structure

```text
CIT-FindIt/
├── client/          # React + Vite frontend
├── server/          # Express REST API
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   └── routes/
│   └── uploads/     # Local development uploads (do not commit user uploads)
├── database/        # PostgreSQL schema and seed scripts
└── README.md
```

## Development status

This repository currently contains the project overview and planned structure. The application modules will be implemented incrementally.

## Getting started

Install Node.js (LTS) and PostgreSQL. The frontend and backend setup commands, environment variables, SQL schema, and API instructions will be documented here as they are added.

**Security note:** Never commit `.env` files, credentials, production data, real student IDs, or private item-ownership details. Use environment variables and synthetic test data during development.

## License

Choose a license before accepting contributions or distributing the project.
