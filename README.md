🗨️ Realtime Chat Application

A modern realtime chat web application built with Next.js, React 19, Elysia, and Upstash Realtime.
It supports low-latency messaging, scalable real-time communication, and a clean developer experience.

🚀 Features

⚡ Realtime messaging using Upstash Realtime

🌐 Full-stack setup with Next.js App Router

🔌 Elysia backend for lightweight, fast APIs

📡 Redis-based pub/sub for message delivery

🧠 Type-safe validation with Zod

🧩 State management & caching via TanStack React Query

🎨 Tailwind CSS for modern UI styling

🔐 Unique message IDs using NanoID

🕒 Time formatting with date-fns

🛠️ Tech Stack
Frontend

Next.js 16

React 19

TypeScript

Tailwind CSS

@tanstack/react-query

Backend

Elysia

@elysiajs/eden

Upstash Realtime

Upstash Redis

Zod




📦 Installation
# Clone the repository
git clone https://github.com/your-username/realtime_chat.git

# Move into the project directory
cd realtime_chat

# Install dependencies
npm install

▶️ Running the App
Development Mode
npm run dev


App runs at:
👉 http://localhost:3000

Production Build
npm run build
npm run start

🔄 Realtime Flow (How It Works)

User sends a message

Backend (Elysia) validates the payload using Zod

Message is published via Upstash Realtime

All subscribed clients receive updates instantly

UI updates automatically via React Query

🧪 Scripts
Command	Description
npm run dev	Start development server
npm run build	Create production build
npm run start	Run production server
npm run lint	Run ESLint
📌 Future Improvements

🔐 Authentication (JWT / OAuth)

👥 User presence & typing indicators

📎 File & image sharing

🔔 Notifications

📱 Mobile-first UI enhancements

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a feature branch

Commit your changes

Open a pull request

📄 License

This project is private and currently not licensed for public distribution.

🙌 Acknowledgements

Upstash for realtime infrastructure

ElysiaJS for fast backend APIs

Next.js & React for frontend power
