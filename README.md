
🧩 Real-Time Whiteboard App
This project is a live collaborative whiteboard that lets users draw, write, and interact in real-time. It supports smooth collaboration with drawing tools, real-time sync, and access control features.


Live demo (deployment) -> https://realtime-boardify.vercel.app/

👨‍💻 Author: Mridul Tyagi


⚡ Features
✏️ Freehand drawing, shapes, text & sticky notes
🎨 Custom colors & dark mode support
🧱 Element layering & arrangement
↩️ Undo / Redo history
⌨️ Handy keyboard shortcuts
🤝 Real-time multi-user sync
🔐 Auth with Clerk & team-based access
⭐ Favorite boards for quick access


🛠 Tech Stack
Next.js 14
Convex (live backend)
Liveblocks (realtime presence)
Clerk (authentication)
TailwindCSS + Shadcn/UI
Zustand + Radix UI



🚀 Setup
git clone https://github.com/your-username/your-repo.git
cd your-repo
npm install


Create .env.local: and fill these variables ->
CONVEX_DEPLOYMENT=""
NEXT_PUBLIC_CONVEX_URL=""
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
NEXT_PUBLIC_LIVE_BLOCKS_DEV_PUBLIC_KEY=""
NEXT_PUBLIC_LIVE_BLOCKS_DEV_SECRET_KEY=""


Run:
npx convex dev
npm run dev
Access: http://localhost:3000


Stay creative and collaborate live!
~ Mridul Tyagi


Let me know if you want a downloadable README.md version or to further customize it.
