# Intertwine

`This is an instant messaging and VoIP social platform which allows communication through voice calls, video calls, text messaging, and media and files. Communication can be private or take place in virtual communities called "servers".`

## Tech Stack

> React, Next.js, TypeScript, TailwindCSS, Shadcn-iu, Socket.io, Clerk, Prisma, PostgreSQL, Supabase, LiveKit, Tanstack/react-query, Uploadthing/react, Axios, Zod, Zustand

#### Install packages

```bash
npm install
```

#### Setup .env file

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

#### Setup Prisma

```bash
npx prisma init
npx prisma generate
npx prisma db push

npm i @prisma/client
npx prisma studio
```

#### Setup Supabase

Create a new project on [Supabase](https://supabase.io/)

- Add your Supabase URL to the .env file
- Add your Supabase public key to the .env file

#### Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
