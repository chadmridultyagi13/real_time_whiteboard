🧩 Real-Time Whiteboard App
This project is a live collaborative whiteboard that lets users draw, write, and interact in real-time. It supports smooth collaboration with drawing tools, real-time sync, and access control features.

🔗 Live Demo -> https://realtime-boardify.vercel.app/
👤 Author: Mridul Tyagi

✨ Features

1)🖊️ Drawing tools: pen, rectangles, circles, text, eraser, color picker

2)⚡ Real-time sync via WebSockets

3)🤝 Multi-user collaboration with shareable sessions

4)🔐 Public/private rooms with edit/view access

5)💾 Export boards as image or PDF

6)↩️ Undo, redo, and clear canvas



🛠 Tech Stack
1)Next.js 14 – Full-stack React framework

2)Convex – Real-time backend

3)Liveblocks – Multiplayer sync & presence

4)Clerk – Authentication & user access

5)TailwindCSS + Shadcn/UI – UI and styling

6)Zustand – Lightweight state management

7)Radix UI – Headless UI primitives



⚙️ Getting Started

git clone https://github.com/your-username/your-repo.git

cd your-repo

npm install


Create a .env.local file:
1)CONVEX_DEPLOYMENT=""

2)NEXT_PUBLIC_CONVEX_URL=""

3)NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""

4)CLERK_SECRET_KEY=""

5)NEXT_PUBLIC_LIVE_BLOCKS_DEV_PUBLIC_KEY=""

6)NEXT_PUBLIC_LIVE_BLOCKS_DEV_SECRET_KEY=""


Run the app:

npx convex dev

npm run dev

Visit: http://localhost:3000

Build, share, and collaborate on whiteboards in real time — all from your browser.
~ Mridul Tyagi

