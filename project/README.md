🧩 Real-Time Whiteboard App
This project is a live collaborative whiteboard that lets users draw, write, and interact in real-time. It supports smooth collaboration with drawing tools, real-time sync, and access control features.

🔗 Live Demo -> https://realtime-boardify.vercel.app/
👤 Author: Mridul Tyagi

✨ Features

🖊️ Drawing tools: pen, rectangles, circles, text, eraser, color picker

⚡ Real-time sync via WebSockets

🤝 Multi-user collaboration with shareable sessions

🔐 Public/private rooms with edit/view access

💾 Export boards as image or PDF

↩️ Undo, redo, and clear canvas



🛠 Tech Stack
Next.js 14 – Full-stack React framework

Convex – Real-time backend

Liveblocks – Multiplayer sync & presence

Clerk – Authentication & user access

TailwindCSS + Shadcn/UI – UI and styling

Zustand – Lightweight state management

Radix UI – Headless UI primitives



⚙️ Getting Started
git clone https://github.com/your-username/your-repo.git
cd your-repo
npm install


Create a .env.local file:
CONVEX_DEPLOYMENT=""

NEXT_PUBLIC_CONVEX_URL=""

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""

CLERK_SECRET_KEY=""

NEXT_PUBLIC_LIVE_BLOCKS_DEV_PUBLIC_KEY=""

NEXT_PUBLIC_LIVE_BLOCKS_DEV_SECRET_KEY=""


Run the app:

npx convex dev

npm run dev

Visit: http://localhost:3000

Build, share, and collaborate on whiteboards in real time — all from your browser.
~ Mridul Tyagi

