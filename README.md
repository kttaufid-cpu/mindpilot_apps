# MindPilot AI - Your Intelligent Life Assistant 
 
> "Your mind, amplified. Your life, simplified." 
 
MindPilot AI is a next-generation AI Personal Assistant app designed for users aged 25–50 who want a smarter way to manage daily life, finances, tasks, routines, and personal productivity. 100% AI-powered with no human backend. 
 
## 🚀 Features 
 
### Core Features 
 
| Feature | Free | Premium | 
|---------|------|---------| 
| **AI Task Manager** | Manual tasks + simple reminders | Auto-generated tasks, priority sorting, location-based reminders | 
| **AI Finance Manager** | Manual tracking + basic stats | Auto categorization, spending insights, bill alerts, financial forecasting | 
| **AI Life Organizer** | Up to 10 documents | Unlimited storage + automatic AI sorting | 
| **AI Wellness Coach** | Mood tracking only | Personalized routines, wellness insights, habit tracking automation | 
| **AI Personal Coach** | Up to 3 goals/month | Unlimited goals + monthly action plans | 
| **Smart Communication** | 15 summaries/day | Unlimited summaries + voice mode + instant message digest | 
 
### Business Model 
 
**FREE VERSION (Lifetime Access)** 
- Lifetime access with limitations 
- Minimal & non-intrusive ads 
- 15 AI responses per day 
- Limited storage (10 documents) 
- Basic summaries only 
 
**PREMIUM VERSION (RM19.90/month)** 
- 7-day free trial 
- Unlimited AI responses 
- Unlimited cloud storage 
- Full automated task management 
- Smart Financial Sync (banks, e-wallets, bills) 
- Advanced daily insights & personalized routines 
- Priority AI processing 
- No ads 
- Encrypted cloud backup 
 
## 🎨 Design 
 
- **Theme**: Cobalt/Teal with Dark Mode 
- **Style**: Minimalist, premium feel 
- **Navigation**: 3-4 main tabs with smooth transitions 
- **UX**: Everything feels intelligent and responsive 
 
## 🛠️ Tech Stack 
 
- **Framework**: Next.js 14 (App Router) 
- **Language**: TypeScript 
- **Styling**: Tailwind CSS 
- **State Management**: Zustand 
- **Animations**: Framer Motion 
- **Icons**: Lucide React 
- **Charts**: Recharts 
 
## 📦 Installation 
 
```bash 
# Install dependencies 
npm install 
 
# Run development server 
npm run dev 
 
# Build for production 
npm run build 
 
# Start production server 
npm start 
``` 
 
## 🚀 Deployment 
 
See [DEPLOYMENT.md](DEPLOYMENT.md) for detailed instructions on deploying to Vercel, Netlify, or using Docker. 
 
**Quick Docker Start:** 
 
```bash 
docker build -t mindpilot-ai . 
docker run -p 3000:3000 mindpilot-ai 
``` 
 
## 🗂️ Project Structure 
 
``` 
src/ 
├── app/ 
│   ├── globals.css      # Global styles 
│   ├── layout.tsx       # Root layout 
│   └── page.tsx         # Main page 
├── components/ 
│   ├── features/ 
│   │   ├── Dashboard.tsx 
│   │   ├── TaskManager.tsx 
│   │   ├── FinanceManager.tsx 
│   │   ├── DocumentManager.tsx 
│   │   ├── WellnessCoach.tsx 
│   │   ├── GoalsCoach.tsx 
│   │   ├── AIAssistant.tsx 
│   │   └── Settings.tsx 
│   ├── layout/ 
│   │   ├── Navigation.tsx 
│   │   └── Header.tsx 
│   ├── ui/ 
│   │   ├── Button.tsx 
│   │   ├── Card.tsx 
│   │   ├── Input.tsx 
│   │   └── Modal.tsx 
│   ├── Onboarding.tsx 
│   └── UpgradeModal.tsx 
└── store/ 
    └── useStore.ts      # Zustand store 
``` 
 
## 🔐 Privacy & Security 
 
- All data stored locally using browser storage 
- No data sent to external servers (demo mode) 
- Premium features include encrypted cloud backup 
- User data never shared with third parties 
 
## 📱 User Journey 
 
1. **Onboarding**: Welcome → Profile Setup → Focus Areas → Plan Selection 
2. **Daily Use**: Dashboard → Tasks/Finance/Wellness → AI Assistant 
3. **Upgrade Triggers**: Usage limits reached → Premium features locked → Trial offer 
 
## 🎯 Positioning 
 
MindPilot AI is positioned as an **all-in-one AI life assistant** that handles: 
- ✅ Task Management 
- ✅ Personal Finance 
- ✅ Daily Routines 
- ✅ Wellness & Health 
- ✅ Document Management 
- ✅ Personal Coaching 
 
All fully automated and personalized through advanced AI. 
 
## 📄 License 
 
MIT License - Feel free to use and modify for your projects. 
 
--- 
 
Built with ❤️ by MindPilot AI Team 
