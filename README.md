# ChanakYA App - LMS with Next.js, Supabase & Payments

## Tech Stack

- **Next.js**: React framework for building fast, scalable web applications
- **Supabase**: Backend-as-a-service platform with PostgreSQL database
- **Clerk**: Authentication and user management
- **Tailwind CSS**: Utility-first CSS framework
- **TypeScript**: Static typing for JavaScript
- **shadcn/ui**: Component library built on Radix UI and Tailwind CSS
- **Vapi**: Voice AI platform for conversational agents
- **Zod**: TypeScript schema validation

## Features

- AI Voice Agents for tutoring sessions
- User authentication with Clerk
- Billing & subscription management
- Bookmarks and session history
- Create custom AI tutors
- Responsive design for all devices
- Real-time database integration with Supabase
- Modern UI/UX with Tailwind CSS and shadcn/ui
- Search functionality for tutors

## Quick Start

### Prerequisites

- Git
- Node.js
- npm

### Installation

```bash
git clone 
cd 
npm install
```

### Environment Setup

Create a `.env` file in the root directory with:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

### Running the Project

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the application. 
