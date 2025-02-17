  <h1 align="center">Modern WhatsApp Clone with AI Features</h1>

<p align="center">
 A feature-rich WhatsApp clone
</p>

<p align="center">
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#installation"><strong>Installation</strong></a>
</p>
<br/>

## Features

- 📞 Real-time video and voice calls
- 💬 Real-time messaging
- 📸 Image and file sharing
- 👥 Group chat functionality
- 🔒 Secure authentication

## Tech Stack

- Next.js 14
- Convex for backend and real-time functionality
- ShadcN UI for modern UI components
- Clerk for authentication
- Tailwind CSS for styling
- ZegoCloud for video/voice calls
- TypeScript for type safety

## Installation

1. Clone the repository

```bash
git clone https://github.com/mr-kasper/whatsapp-clone.git
cd whatsapp-clone
```

2. Install dependencies

```bash
npm install
# or
yarn install
```

3. Configure environment variables:

- Create a `.env.local` file with:
  - `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`
  - `CLERK_SECRET_KEY`
  - `ZEGO_APP_ID`
  - `ZEGO_SERVER_SECRET`

4. Set up Convex:

- Run `npx convex dev`
- Add these environment variables in Convex dashboard:
  - `CLERK_ISSUER_URL`
  - `CLERK_WEBHOOK_SECRET`
  - `OPENAI_API_KEY`

5. Run the development server

```bash
npm run dev
# or
yarn dev
```

Visit [http://localhost:3000](http://localhost:3000) to see your app.
