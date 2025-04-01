# 🎯 MockMate

MockMate is a cutting-edge platform that helps job seekers practice and improve their interview skills using AI voice agents powered by Vapi and Google Gemini.

## ✨ Features

### Core Functionality
- **🔐 Authentication**: Sign Up and Sign In using password/email authentication handled by Firebase.
- **🤖 Create Interviews**: Easily generate job interviews with help of Vapi voice assistants and Google Gemini.
- **📊 Get feedback from AI**: Take the interview with AI voice agent, and receive instant feedback based on your conversation.
- **📱 Responsiveness**: Fully responsive design that works seamlessly across devices.

### UI Components
- **💼 Interview Page**: Conduct AI-driven interviews with real-time feedback and detailed transcripts.
- **📈 Dashboard**: Manage and track all your interviews with easy navigation.
- **🎨 Modern UI/UX**: A sleek and user-friendly interface designed for a great experience.

## 🛠️ Tech Stack

- **Frontend**: Next.js, TypeScript, Tailwind CSS
- **Backend**: Next.js API routes with TypeScript
- **Authentication**: Firebase Authentication
- **Database**: Firebase Firestore
- **AI Integration**: Vapi for voice assistants, Google Gemini for interview generation and feedback
- **Deployment**: Vercel


## 🤸 Quick Start

### VS Code Commands

1. **Open the project in VS Code**
   ```bash
   code .
   ```

2. **Initialize Git repository (if not already initialized)**
   ```bash
   git init
   ```

3. **Stage all files**
   ```bash
   git add .
   ```

4. **Commit your changes**
   ```bash
   git commit -m "Initial commit"
   ```


### Standard Setup

1. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

2. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the application running.

## 📦 Code Reusability

The codebase is designed with reusability in mind:

- **Component Library**: UI components are built to be reusable across the application.
- **Custom Hooks**: Business logic is encapsulated in custom hooks for better separation of concerns.
- **Context API**: Global state management using React Context for authentication and user data.
- **TypeScript**: Strong typing ensures code reliability and better developer experience.
- **Utility Functions**: Common operations are abstracted into utility functions for DRY code.


## 🧪 Testing

```bash
# Run unit tests
npm run test
# or
yarn test

# Run e2e tests
npm run cypress
# or
yarn cypress
```

---

Built with ❤️ by Karan (Paul)