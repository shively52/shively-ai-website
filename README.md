# Shively AI - AI Receptionist Platform

An advanced AI-powered receptionist and automation platform website designed to help businesses streamline their customer interactions and automate routine tasks. Shively AI provides intelligent virtual receptionist services that can handle calls, schedule appointments, answer questions, and integrate seamlessly with existing business workflows.

## 🚀 Features

- **AI-Powered Virtual Receptionist**: Intelligent call handling and customer service automation
- **Appointment Scheduling**: Automated booking and calendar management
- **Business Integration**: Seamless integration with existing CRM and business tools
- **24/7 Availability**: Round-the-clock customer support automation
- **Multi-Language Support**: Serve customers in multiple languages
- **Analytics Dashboard**: Comprehensive insights into customer interactions

## 🛠️ Tech Stack

- **Frontend Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) for type-safe development
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for utility-first styling
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/) for modern, accessible components
- **Icons**: [Lucide React](https://lucide.dev/) for beautiful icons
- **Package Manager**: [Bun](https://bun.sh/) for fast package management

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 18 or higher)
- [Bun](https://bun.sh/) (recommended) or npm

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/shively52/shively-ai-website.git
   cd shively-ai-website
   ```

2. **Install dependencies**
   ```bash
   bun install
   ```

3. **Run the development server**
   ```bash
   bun dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📜 Available Scripts

- `bun dev` - Start the development server with Turbopack
- `bun build` - Build the application for production
- `bun start` - Start the production server
- `bun lint` - Run linting and type checking
- `bun format` - Format code using Biome

## 🏗️ Project Structure

```
shively-ai-website/
├── src/
│   ├── app/                # Next.js app directory
│   │   ├── globals.css     # Global styles
│   │   ├── layout.tsx      # Root layout component
│   │   └── page.tsx        # Home page
│   ├── components/         # Reusable UI components
│   │   └── ui/            # shadcn/ui components
│   └── lib/               # Utility functions
├── public/                # Static assets
├── .gitignore            # Git ignore rules
├── package.json          # Dependencies and scripts
├── tailwind.config.ts    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
└── README.md            # Project documentation
```

## 🎨 UI Components

This project uses [shadcn/ui](https://ui.shadcn.com/) components for a consistent and modern design system. To add new components:

```bash
npx shadcn@latest add -y -o [component-name]
```

## 🚀 Deployment

### Netlify (Recommended)
This project is optimized for deployment on Netlify:

1. Connect your GitHub repository to Netlify
2. Set the build command to `bun run build`
3. Set the publish directory to `.next`
4. Deploy!

### Vercel
For Vercel deployment:

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is proprietary software owned by Shively AI. All rights reserved.

## 📞 Contact

For questions or support regarding the Shively AI platform, please contact our team.

---

Built with ❤️ by the Shively AI team