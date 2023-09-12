# ChatFusion: Real-Time Messaging Redefined

Introducing a cutting-edge message web application that brings real-time communication to life. Our feature-packed platform offers seamless message notifications, stunning Tailwind-designed UI with animations, and full responsiveness across all devices. Enjoy secure credential authentication with NextAuth, along with easy integration with Google and GitHub authentication. Effortlessly upload files and images via Cloudinary CDN, and streamline form validation with react-hook-form. Handle server errors gracefully with react-toast, enable message read receipts, and track user status online/offline. Engage in group chats and one-on-one messaging, share attachments, customize user profiles, and fine-tune settings. Learn how to create, fetch, and delete data with POST, GET, and DELETE routes in our route handlers, and explore direct database access in server React components. Seamlessly manage relationships between server and child components in a real-time environment, and effortlessly create and oversee chat rooms and channels. Elevate your messaging experience with our feature-rich, user-friendly message web app.

## Messenger

Key Features:

- Real-time messaging using Pusher
- Message notifications and alerts
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with NextAuth
- Google authentication integration
- Github authentication integration
- File and image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings
- How to write POST, GET, and DELETE routes in route handlers (app/api)
- How to fetch data in server React components by directly accessing the database (WITHOUT API! like Magic!)
- Handling relations between Server and Child components in a real-time environment
- Creating and managing chat rooms and channels

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
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

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |
