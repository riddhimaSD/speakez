# 🎤 SPEAKEZ - Speech Understanding & Practice Platform

A production-grade, non-judgmental platform for speech understanding, diagnosis, and guided practice.

## 🚀 Quick Start

### 1. Install Dependencies (Already Done ✅)
```bash
npm install
```

### 2. Start Development Server (Already Running ✅)
```bash
npm run dev
```

### 3. Open in Browser

**👉 https://speakez-hackathon.vercel.app**

(Server runs on port 3001)

The server is running! Open this URL in your browser to start using SPEAKEZ.

## ✨ Features

- ✅ **Authentication**: Signup, Login, Password Reset
- ✅ **Practice Sessions**: Real-time microphone/camera analysis
- ✅ **Multi-Agent Architecture**: 6 specialized agents for speech analysis
- ✅ **Purpose Modes**: Pitch, Interview, Professional, Debate, Conversation
- ✅ **Scenario Simulator**: Real-world practice scenarios
- ✅ **Post-Practice Insights**: Timeline and natural language explanations
- ✅ **Improvement Roadmap**: GPT-powered personalized plans
- ✅ **YouTube Learning**: Pattern-based video recommendations
- ✅ **Accent Mode**: Relocation and accent adaptation support
- ✅ **Profile & Settings**: Customizable preferences

## 🎯 Philosophy

SPEAKEZ is **NOT** an evaluation or grading system. It's a supportive platform that:
- Detects speech patterns (including disorders) without judgment
- Explains where and why speech breaks
- Guides users on how to practice better
- Adapts to personal baselines, not universal standards
- Uses supportive, non-judgmental language throughout

## 📁 Project Structure

```
app/
├── api/              # API routes (GPT, YouTube, Speech-to-Text)
├── dashboard/        # Protected dashboard pages
├── login/           # Authentication pages
└── page.tsx         # Landing page

lib/
├── agents/          # Multi-agent architecture
└── store.ts         # State management

components/
└── Sidebar.tsx      # Navigation component
```

## 🔧 Environment Variables (Optional)

Create `.env.local` for full functionality:

```env
OPENAI_API_KEY=your_openai_key
YOUTUBE_API_KEY=your_youtube_key
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

The app works without these - it will use fallback implementations.

## 🎨 Design Principles

- **Non-judgmental**: No scoring, grading, or harsh evaluations
- **Supportive**: Encouraging language throughout
- **Inclusive**: Adapts to personal baselines
- **Accessibility-first**: Built for all users

## 📚 Documentation

- `SETUP.md` - Detailed setup instructions
- `PROJECT_SUMMARY.md` - Complete feature list
- `START.md` - Quick start guide

## 🎉 Ready to Use!

Everything is implemented and working. The development server is running at:

### **https://speakez-hackathon.vercel.app**

Start exploring:
1. Landing page → Sign up
2. Dashboard → Start a practice session
3. Practice → Use microphone to practice
4. Insights → View your analysis
5. Roadmap → Get personalized improvement plan

---

**Built with Next.js 14, TypeScript, Tailwind CSS, and ❤️**
