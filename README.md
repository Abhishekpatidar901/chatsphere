# Chatsphere - Multifunctional Digital Community Communication Platform

Chatsphere is a real-time communication platform developed using Next.js, providing server-based organization. It integrates text messaging with Socket.io, audio and video calls with Livekit, and attachments with UploadThing. The platform features a fully responsive user interface designed with TailwindCSS and ShadcnUI, utilizing Prisma ORM with MySQL for efficient data operations and Clerk for secure authentication. The app is deployed on Railway.app with GitHub, using Neon DB Postgres for persistent WebSocket support.

## Introduction

Chatsphere is a full-stack Discord clone built with the latest technologies to provide a robust and scalable communication platform. It supports real-time messaging, audio and video calls, and various community management features. The application is designed to be highly responsive, ensuring a seamless user experience across all devices.

## Key Features

- **Real-time Messaging**: Integrated with Socket.io for real-time text messaging.
- **Audio and Video Calls**: Supports 1:1 and group audio and video calls using Livekit.
- **Attachments**: Users can send attachments as messages using UploadThing.
- **Message Management**: Allows users to delete and edit messages in real time.
- **Channels**: Create text, audio, and video call channels.
- **1:1 Conversations and Calls**: Supports direct messaging and video calls between members.
- **Member Management**: Manage members with roles (Guest / Moderator) and kick functionality.
- **Invite System**: Generate unique invite links and manage invites.
- **Infinite Loading**: Implements infinite loading for messages in batches of 10 using tanstack/query.
- **Server Creation and Customization**: Users can create and customize their servers.
- **Responsive UI**: Fully responsive user interface with light and dark modes.
- **WebSocket Fallback**: Fallback to polling with alerts if WebSocket connection fails.
- **ORM**: Utilizes Prisma for efficient data operations.
- **Database**: MySQL database managed with Planetscale.
- **Authentication**: Secure authentication using Clerk.

## Technologies Used

- **Frontend**:
  - Next.js 13
  - React.js
  - TailwindCSS
  - ShadcnUI
  - Socket.io
  - React-hook-form
  - UploadThing
  - tanstack/query

- **Backend**:
  - Node.js
  - Express
  - Livekit
  - Prisma ORM
  - MySQL (Planetscale)
  - Neon DB Postgres
  - SocketIO
  - Clerk (authentication)
