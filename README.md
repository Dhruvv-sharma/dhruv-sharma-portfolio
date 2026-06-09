# Dhruv Sharma Portfolio

A responsive full-stack developer portfolio built with React, Vite, Framer Motion,
Express, and MySQL.

## Features

- Animated dark glassmorphism portfolio
- Responsive mobile, tablet, and desktop layouts
- Project filtering and database-backed project cards
- Contact form with server-side validation
- Admin dashboard at `/#admin`
- GitHub and LeetCode profile panels
- Resume download and visitor counter
- REST API for project CRUD and contact messages

## Local setup

1. Install packages:

   ```bash
   npm install
   ```

2. Create the database:

   ```bash
   mysql -u root -p < database/schema.sql
   ```

3. Copy `.env.example` to `.env` and update the MySQL credentials and admin key.

4. Start the API:

   ```bash
   npm run server
   ```

5. In a second terminal, start Vite:

   ```bash
   npm run dev
   ```

The portfolio runs at `http://localhost:5173` and the API runs at
`http://localhost:5000`.

## Personalization

- Replace `public/resume-placeholder.txt` with `public/resume.pdf`, then update the
  two resume links.
- Update the GitHub, LinkedIn, LeetCode, email, project, and certification values.
- Replace `public/assets/dhruv-developer.png` with a real portrait if preferred.
