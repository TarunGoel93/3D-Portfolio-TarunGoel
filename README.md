# Tarun Goel's 3D Interactive Portfolio
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/TarunGoel93/3D-Portfolio-TarunGoel)

Welcome to my 3D interactive portfolio, a creative showcase of my skills as an AI/ML and Frontend Developer. This project is more than just a resume; it's a dynamic and engaging experience built with a modern tech stack including Next.js, Spline, and Framer Motion. It features real-time interactions, intricate animations, and a unique 3D keyboard to explore my technical abilities.


A live version of the website can be viewed here: **[https://github.com/TarunGoel93/3D-Portfolio-TarunGoel](https://github.com/TarunGoel93/3D-Portfolio-TarunGoel/)**  



## ✨ Key Features

-   **🚀 3D Interactive Experience**: A fully interactive 3D keyboard, crafted with Spline, animates based on scroll position and user input to dynamically display skills.
-   **🌐 Real-Time Collaboration**: See who else is visiting! The site features real-time cursors, an online user counter, and a mini-chat functionality powered by Socket.IO.
-   **✨ Fluid Animations & Transitions**: Leverages GSAP and Framer Motion for smooth page transitions, reveal-on-scroll effects, and a custom elastic cursor that enhances user interaction.
-   **📜 Smooth Scrolling**: Implements `lenis` for a seamless and pleasant scrolling experience across all sections.
-   **🎨 Custom UI Components**: A rich set of UI elements including animated modals, a floating dock for project skills, and custom inputs built on top of shadcn/ui and inspired by Aceternity UI.
-   **💌 Integrated Contact Form**: A fully functional contact form that uses the Resend API to deliver messages directly to my inbox.
-   **👾 Easter Eggs**: For the curious, there are hidden surprises in the browser console and a Nyan Cat triggered by a secret key press.

## 🛠️ Tech Stack

-   **Framework**: [Next.js](https://nextjs.org/)
-   **Language**: [TypeScript](https://www.typescriptlang.org/)
-   **Styling**: [Tailwind CSS](https://tailwindcss.com/)
-   **UI Libraries**: [shadcn/ui](https://ui.shadcn.com/), [Aceternity UI](https://ui.aceternity.com/)
-   **3D Rendering**: [Spline](https://spline.design/)
-   **Animation**: [Framer Motion](https://www.framer.com/motion/), [GSAP](https://gsap.com/)
-   **Real-time Communication**: [Socket.IO](https://socket.io/)
-   **Backend Service (Email)**: [Resend](https://resend.com/)
-   **Analytics**: [Umami](https://umami.is/)

## 🚀 Getting Started

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/TarunGoel93/3D-Portfolio-TarunGoel.git
cd 3D-Portfolio-TarunGoel
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env.local` file in the root of the project and add the following variables.

```env
# Resend API Key for the contact form
RESEND_API_KEY="your_resend_api_key"

# URL for the WebSocket server (for real-time features)
NEXT_PUBLIC_WS_URL="http://localhost:3001" # or your deployed server URL

# Umami Analytics (optional)
UMAMI_DOMAIN="your_umami_script_url"
UMAMI_SITE_ID="your_umami_website_id"
```

### 4. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📂 Project Structure

```
└── src
    ├── app/                # Next.js App Router: pages, layouts, and API routes
    │   ├── api/            # API routes (e.g., contact form handler)
    │   └── (pages)/        # Main pages (Home, About, Projects, etc.)
    ├── components/         # Reusable React components
    │   ├── sections/       # Major page sections (Hero, Skills, etc.)
    │   ├── ui/             # UI elements from shadcn/ui and custom components
    │   ├── header/         # Animated header component
    │   └── realtime/       # Components for real-time features (cursors, chat)
    ├── contexts/           # React context providers (e.g., Socket.IO)
    ├── data/               # Static data, constants, and project details
    ├── hooks/              # Custom React hooks
    ├── lib/                # Utility functions and library configurations
    └── public/             # Static assets (images, Spline scenes)
```

## 🙏 Acknowledgements

This project was made possible with inspiration and tools from jatuh. Credits to:
-   **shadcn/ui** for the foundational UI components.
-   **Aceternity UI** for advanced UI component ideas and animations.
-   **Studio Lumio** for the inspiration behind the animated header design.
