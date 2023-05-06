# NextJS 13 Startup Repository README

This repo is designed to help you get started quickly with a new project using the NextJS 13 app dir with prisma, and next-auth configured.

## Prerequisites

Ensure that you have Node.js (v16 or higher) and npm (v7 or higher) installed on your system. You can check your current versions by running the following commands:

```bash
node -v
npm -v
```

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/RobPruzan/nextjs-13-startup.git
```

2. Change into the newly created directory:

```bash
cd nextjs-13-startup-repo
```

3. Install the required dependencies:

```bash
npm install
```

## Configuration

1. Rename the `.env.example` file to `.env`:

```bash
mv .env.example .env
```

2. Obtain the necessary credentials for authentication and database setup, and update the `.env` file accordingly. You'll need to provide the following:

- Client IDs and secrets
- Database URLs

## Database Setup

1. Run the Prisma migration to set up the database schema:

```bash
npx prisma migrate dev
```

## Running the Development Server

1. Start the development server on port 3000:

```bash
npm run dev
```

2. Open your browser and navigate to `http://localhost:3000` to view your NextJS 13 application.
