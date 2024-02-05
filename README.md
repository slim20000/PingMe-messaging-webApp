# Real-Time Messaging App

This Real-Time Messaging App is built with Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher, and Cloudinary. It provides real-time messaging using Pusher, message notifications, and alerts. The sleek UI design is achieved with Tailwind, and it includes animations and transition effects.

## Features

- Real-time messaging with Pusher
- Message notifications and alerts
- Tailwind design for a sleek UI
- Full responsiveness for all devices
- Credential authentication with NextAuth
- Google and GitHub authentication integration
- File and image upload using Cloudinary CDN
- Client form validation using react-hook-form
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings
- POST, GET, and DELETE routes in route handlers (app/api)
- Fetching data in server React components by directly accessing the database
- Handling relations between server and child components in a real-time environment
- Creating and managing chat rooms and channels

## Prerequisites

- Node version 14.x

## Installation

1. **Install packages:**

   ```bash
   npm install

   ## Setup .env File

```dotenv
DATABASE_URL=your_mongo_db_url
NEXTAUTH_SECRET=your_nextauth_secret
NEXT_PUBLIC_PUSHER_APP_KEY=your_pusher_app_key
PUSHER_APP_ID=your_pusher_app_id
PUSHER_SECRET=your_pusher_secret
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
GITHUB_ID=your_github_id
GITHUB_SECRET=your_github_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

