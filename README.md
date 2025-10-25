# 🌍 AI Trip Planner

![AI Trip Planner Logo](/public/logo.svg)

AI Trip Planner is a modern web application that leverages artificial intelligence to create personalized travel itineraries. Built with React, Vite, and powered by Google's Generative AI, this application helps users plan their perfect trip with minimal effort.

![Landing Page](/public/landing.png)

## ✨ Features

- **AI-Powered Trip Generation**: Create detailed trip itineraries based on your preferences
- **Location Search**: Find destinations using Google Places API
- **Trip Management**: Save, view, and manage your planned trips
- **User Authentication**: Secure login with Google OAuth
- **Responsive Design**: Beautiful UI that works on desktop and mobile devices
- **Dark/Light Mode**: Choose your preferred theme for comfortable viewing

## 🚀 Live Demo

Visit [AI Trip Planner](https://ai-trip-planner.vercel.app) to see the application in action.

## 🛠️ Technologies Used

- **Frontend**: React, TailwindCSS, Shadcn UI
- **State Management**: React Context API
- **Authentication**: Firebase Authentication, Google OAuth
- **Database**: Firebase Firestore
- **AI Integration**: Google Generative AI
- **Deployment**: Vercel
- **Build Tool**: Vite

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v16 or higher)
- npm or yarn package manager

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-trip-planner.git
cd ai-trip-planner
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Variables

Create a `.env` file in the root directory with the following variables:

```
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
VITE_GOOGLE_AI_API_KEY=your_google_ai_api_key
VITE_GOOGLE_CLIENT_ID=your_google_client_id
```

### 4. Start the development server

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`.

## 📱 Usage

1. **Sign In**: Use your Google account to sign in
2. **Create a Trip**: 
   - Enter your destination
   - Specify trip dates
   - Set your preferences (budget, interests, etc.)
   - Click "Generate Trip"
3. **View Trip**: Explore your AI-generated itinerary with day-by-day activities
4. **Save Trip**: Save your trip to access it later
5. **My Trips**: View all your saved trips in one place

## 🧰 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint

## 🔄 Deployment

This project is configured for easy deployment to Vercel. Simply connect your GitHub repository to Vercel and it will automatically deploy when you push changes.

For manual deployment:

```bash
npm run build
vercel --prod
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

If you have any questions or feedback, please reach out at [your-email@example.com](mailto:your-email@example.com).

---

Made with ❤️ using React, Vite, and Google's Generative AI