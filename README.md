# Ultimate AI Application

## Core Features:

- NextJS 13
- Server Components
- Tailwind CSS
- Full responsiveness
- Clerk Authentication (Email, Google, & other Social Logins)
<!-- - react-hook-form -->
- Server error handling using react-toast
- Stripe monthly subscription

## AI tools Integrated

- Image Generation Tool (Open AI)
- Video Generation Tool (Replicate AI)
- Conversation Generation Tool (Open AI)
- Music Generation Tool (Replicate AI)
  Also, Free tier with API limiting

> Must Have: **Node version `18.x.x`**

### Package Install

```shell
npm install
```

### Setting up the `.env` file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard

OPENAI_API_KEY=
REPLICATE_API_TOKEN=

DATABASE_URL=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

NEXT_PUBLIC_APP_URL="http://localhost:3000"
```

### Setup Prisma

- use `Prisma` with any Platform you want.

### Starting the AI application

```shell
npm run dev
```
