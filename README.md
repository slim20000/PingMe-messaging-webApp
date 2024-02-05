# Real-Time Messaging App

A real-time messaging web-app built with Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, and Pusher. You can check out the live app [here](https://ping-me-messaging-web-fm3j8c8z1-slim20000s-projects.vercel.app/).

## Features

- Real-time messaging using Pusher
- Message notifications and alerts
- Sleek UI with Tailwind design and animations
- Full responsiveness for all devices
- Credential and social authentication (Google, GitHub) with NextAuth
- File and image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings

## Prerequisites

- Node version 14.x

## Setup

1. Install packages: `npm i`
2. Setup `.env` file with your configuration:
    ```
    DATABASE_URL=
    NEXTAUTH_SECRET=
    NEXT_PUBLIC_PUSHER_APP_KEY=
    PUSHER_APP_ID=
    PUSHER_SECRET=
    NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
    GITHUB_ID=
    GITHUB_SECRET=
    GOOGLE_CLIENT_ID=
    GOOGLE_CLIENT_SECRET=
    ```
3. Setup Prisma: `npx prisma db push`
4. Start the app: `npm run dev`
