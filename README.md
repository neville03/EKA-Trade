# EKA

> Premium Accessories Marketplace — live at [eka.com](https://www.eka.com)

---

## Overview

**EKA** is an experimental full-stack e-commerce platform specialising in premium accessories. The platform delivers a seamless shopping experience with a modern, responsive interface and a robust backend for product and order management.

## Features

- 🛍️ Product catalogue with browsing and filtering
- 🛒 Shopping cart and streamlined checkout flow
- 👤 User authentication and account management
- 📦 Order tracking and history
- 🔒 Secure data handling via Supabase
- 📱 Fully responsive across mobile, tablet, and desktop

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + Vite |
| Styling | Tailwind CSS |
| Backend | Supabase |
| Database | MySQL |
| Deployment | *(e.g. Vercel, Netlify — update as needed)* |

## Getting Started

```bash
# Clone the repository
git clone https://github.com/neville04/eka.git
cd eka

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Environment Variables

Create a `.env` file in the root of the project:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

> Never commit your `.env` file. Ensure it is listed in `.gitignore`.

## Project Structure

```
eka/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── lib/
│   └── main.jsx
├── .env
├── index.html
├── tailwind.config.js
└── vite.config.js
```

## Deployment

*(Update with live URL once deployed)*

## Notes

This is an experimental platform — features and architecture are subject to change as the project evolves.

---

*Developed by [Neville](https://github.com/neville04)*
