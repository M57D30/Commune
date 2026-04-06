# Breadit — Full-Stack Reddit Clone

A modern Reddit-like social discussion platform built with **Next.js 14**, following the popular "Build and Deploy a Fullstack Reddit Clone" tutorial by Josh tried coding.

Users can create communities (subreddits), post content, comment with nested replies, vote on posts and comments, and browse personalized or general feeds.

## ✨ Key Features

- Create and join communities (subreddits)
- Post creation with rich text editor, image uploads, and link previews
- Infinite scrolling feed with custom feeds for logged-in users
- Upvote / downvote system on posts and comments
- Nested comment threads with replies
- User authentication (Google OAuth via NextAuth)
- Optimistic UI updates for smooth voting and interactions
- Advanced caching and performance optimizations
- Responsive design with beautiful UI
- Search functionality and user profile settings

## 🛠 Tech Stack

- **Framework**: Next.js 14 (App Router, Server & Client Components)
- **Language**: TypeScript
- **Styling**: Tailwind CSS + shadcn/ui components
- **Database**: Prisma ORM (MySQL compatible)
- **Authentication**: NextAuth.js with Google provider
- **Data Fetching & Mutations**: React Query (TanStack Query)
- **Other**: Lucide React icons, Zod validation, Vercel deployment

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/M57D30/breadit.git
cd breadit

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
# Add your DATABASE_URL, Google OAuth credentials, and any other keys

# 4. Set up the database
npx prisma generate
npx prisma db push   # or npx prisma migrate dev

# 5. Run the development server
npm run dev
