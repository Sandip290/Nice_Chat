NiceChat - Video Conferencing Platform

NiceChat is a fully responsive video conferencing web application built with Next.js and TypeScript. It enables users to create, join, and schedule meetings while providing access to previous meeting recordings. The platform is designed for seamless user experience and enhanced real-time interactions.

🚀 Features

- User Authentication: Secure login and signup using Clerk.
- Create & Join Meetings: Generate unique meeting links or join existing meetings.
- Meeting Controls: Mute/unmute, screen share, and manage participants.
- Scheduled Meetings: Plan and organize future meetings with ease.
- Past Meeting Recordings: Access and review previous meetings.
- Sentiment Analysis: Real-time analysis of participants' emotions.
- Virtual Assistance: AI-powered meeting assistance.
- Background Noise Suppression: Enhanced audio clarity for better communication.
- Fully Responsive: Optimized for desktop and mobile devices.

🛠 Tech Stack

- Frontend: Next.js, TypeScript, Tailwind CSS, shadcn
- Authentication: Clerk
- Video Streaming: WebRTC, Stream
- Backend: Node.js, Express.js, MongoDB
- AI Features: Sentiment Analysis & Noise Suppression

🚀 Getting Started

Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)

### Installation

Clone the repository:
```bash
git clone https://github.com/your-username/nicechat.git
cd nicechat
```

Install dependencies:
```bash
npm install
```

### Environment Variables

Create a `.env` file and configure the required credentials:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

### Run the Application

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

📌 Future Enhancements

- Integration with Calendar APIs
- AI-powered Meeting Summarization
- Custom Meeting Room Themes

---

Enjoy seamless video conferencing with NiceChat! 🎥🚀

