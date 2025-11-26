# Login (Node.js + Express + HBS)

<img width="1914" height="880" alt="image" src="https://github.com/user-attachments/assets/3c47d379-d2b8-451f-9f6b-33cc79efbed5" />

## Overview
A minimal login demo built with Express and Handlebars (HBS). It demonstrates session-based authentication using [`express-session`](package.json), client-side validation, and a simple UI styled with Bootstrap and [`public/style.css`](public/style.css). The application routes and hard-coded credentials (for demo only) are defined in [`Routes/user.js`](Routes/user.js), and the server setup is in [`server.js`](server.js).

## Features
- Session-based login using [`express-session`](package.json)
- Router-driven structure in [`Routes/user.js`](Routes/user.js)
- Handlebars templates for views: [`views/login.hbs`](views/login.hbs) and [`views/home.hbs`](views/home.hbs)
- Client-side validation on the login form
- Bootstrap-based UI + custom styles in [`public/style.css`](public/style.css)
- Demo credentials (hard-coded in [`Routes/user.js`](Routes/user.js)): username `msn04`, password `msn01234`
- Simple logout flow and nocache usage to prevent caching

## Live Demo
https://user-login-94ux.onrender.com/
