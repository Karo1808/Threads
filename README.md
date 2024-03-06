# Threads 

[![pl](https://img.shields.io/badge/lang-pl-red.svg)](https://github.com/YourUsername/ThreadsPlatform/blob/main/README.pl.md)

### Description

Threads is a web application designed to facilitate community interactions and discussions based on Threads by Meta. It offers a range of features aimed at creating engaging and inclusive online communities.

This web application was built following a tutorial by [Java Script Mastery](https://www.youtube.com/watch?v=O5cmLDVTgAs).

### Demo

[Visit the website](https://threads-app-karo.vercel.app/)

### Features

- **Authentication**
  - Secure user authentication system provided by Clerk, supporting email, password, and social logins (Google and GitHub), with comprehensive profile management.
- **Visually Appealing Home Page**
  - A visually engaging home page showcasing the latest threads for an immersive user experience.
- **Create Thread Page**
  - Dedicated space for users to create threads, fostering community engagement and discussions.
- **Commenting Feature**
  - Interactive commenting feature enabling users to participate in thread discussions.
- **Nested Commenting**
  - Commenting system with nested threads for organized and structured conversations.
- **User Search with Pagination**
  - Discover and explore other users with a search feature and pagination for ease of navigation.
- **Activity Page**
  - Notifications for thread comments displayed on the activity page to enhance user engagement.
- **Profile Page**
  - Personalized user profile pages for managing profile settings and showcasing information.
- **Create and Invite to Communities**
  - Create new communities and invite others using customizable template emails for community expansion.
- **Community Member Management**
  - User-friendly interface for managing community members, allowing role changes and removals.
- **Admin-Specific Community Threads**
  - Admins can create threads specifically for their community, fostering community-specific discussions.
- **Community Search with Pagination**
  - Discover and explore different communities with a search feature and pagination for efficient browsing.
- **Community Profiles**
  - Detailed community profiles showcasing threads and members for a comprehensive overview.

### Technologies Used

- **Next.js 13**
  - A React framework for building server-side rendered applications.
- **MongoDB**
  - NoSQL database for managing complex schemas and data populations.
- **Shadcn UI**
  - Component library for building user interfaces.
- **Tailwind CSS**
  - A utility-first CSS framework for creating custom designs with ease.
- **Clerk**
  - Authentication provider for secure user authentication.
- **Webhooks**
  - Real-time event listening for notifications and updates.
- **React Hook Form**
  - Form management library for streamlined user input experience.
- **Zod**
  - Data validation library for ensuring data integrity.
- **TypeScript**
  - A superset of JavaScript for enhanced code quality and developer productivity.
- **Uploadthing**
  - File upload service

#### Installation

Clone the repository locally

```bash
git clone https://github.com/Karo1808/Threads.git
```

Install the required dependencies

```bash
npm install
```

Create an .env.local file and add the following environment variables

```bash
NEXT_CLERK_WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
MONGODB_URL=
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

Run the website locally

```bash
npm run dev
```
