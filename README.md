# 🎬 Movie Explorer – Phase 3

## ⚠ IMPORTANT – Environment Variable Required

This project requires a **TMDB API v4 Bearer Token** to fetch movies.

## 🔒 Security Note

The `.env.local` file is not included in this repository for security reasons.

Use `.env.example` as a reference for required variables.

### Setup Instructions

1. Create a file in the root directory named:

.env.local

2. Add your TMDB API Read Access Token (v4):

TMDB_API_KEY=your_tmdb_v4_bearer_token_here

⚠ Do NOT include quotes.  
⚠ Restart the development server after creating this file.

You can obtain your token from:

TMDB Dashboard → Settings → API → API Read Access Token

---

## 📌 Overview

Phase 1 of the Movie Explorer application.

This phase focuses on:

- Fetching popular movies from TMDB
- Server-side data fetching
- Basic rendering using Next.js App Router
- Error handling

---

## 🚀 Features Implemented

- Fetch popular movies from TMDB API
- Display movie list
- Graceful error handling
- Clean component structure

---

## 🛠 Tech Stack

- Next.js (App Router)
- TypeScript
- TMDB API
- ESLint

---

## 📦 Run Locally

1. Clone the repository:

git clone <your-repo-link>

2. Install dependencies:

npm install

3. Start development server:

npm run dev

4. Open in browser:

http://localhost:3000

---
