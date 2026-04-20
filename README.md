# pm-app-aws

A full-stack Project Management Application built with Next.js, Node.js, and PostgreSQL — deployed on AWS.

> 🚧 **Status: Currently in active development**

---

## Tech Stack

**Frontend**
- Next.js
- Tailwind CSS

**Backend**
- Node.js
- REST APIs

**Database**
- PostgreSQL (AWS RDS)

**Cloud & Auth**
- AWS EC2 (hosting)
- AWS Cognito (authentication)
- AWS RDS (database)

---

## Features (Planned)

- [ ] User authentication via AWS Cognito
- [ ] Create and manage projects
- [ ] Task assignment and tracking
- [ ] Team collaboration
- [ ] Real-time status updates
- [ ] Cloud-deployed and production-ready

---

## Architecture

```
Client (Next.js) → AWS EC2 (Node.js API) → AWS RDS (PostgreSQL)
                          ↑
                   AWS Cognito (Auth)
```

---

## Getting Started

```bash
# Clone the repository
git clone git clone https://github.com/yourusername/pm-app-aws.git

# Install dependencies
cd pm-app-aws
npm install

# Run development server
npm run dev
```

> Full setup guide and environment variables documentation coming soon.

---

## Deployment

This project is deployed on AWS using:
- **EC2** — backend server hosting
- **RDS** — managed PostgreSQL database
- **Cognito** — user authentication and authorization

---

## Author

**Your Name** — B.Tech CS (AI & ML) Student
- GitHub: [@ayushsamor21](https://github.com/ayushsamor21)
- LinkedIn: [linkedin.com/in/ayush-samor](https://www.linkedin.com/in/ayush-samor-6a579b403/)

---

> This project is part of my journey toward becoming an AI/ML and Cloud Engineer.
