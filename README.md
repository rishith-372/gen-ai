# NutriPlan - Smart Nutrition & Meal Planning

A modern web application for food nutrition analysis and personalized meal planning using AI.

## Features

- **Food Analysis**: Get detailed nutritional information for any food item
- **Image Recognition**: Upload food images for automatic analysis
- **Meal Planning**: Generate personalized meal plans based on preferences
- **Budget Planning**: Track and manage meal costs
- **Smart Recommendations**: AI-powered recipe and meal suggestions

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Gemini API key

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Install required packages:
```bash
npm install @radix-ui/react-tabs @radix-ui/react-separator @radix-ui/react-slot @tanstack/react-query framer-motion lucide-react react-helmet react-router-dom sonner tailwindcss @types/react @types/react-dom @vitejs/plugin-react autoprefixer postcss typescript vite
```

4. Create a `.env` file in the root directory and add your Gemini API key:
```env
VITE_GEMINI_API_KEY=your_api_key_here
```

5. Start the development server:
```bash
npm run dev
# or
yarn dev
```

## Environment Variables

- `VITE_GEMINI_API_KEY`: Your Google Gemini API key for AI features

## Tech Stack

- React
- TypeScript
- Vite
- TailwindCSS
- React Query
- Framer Motion
- Google Gemini AI

## Development

To start the development server:

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## Building for Production

```bash
npm run build
# or
yarn build
```

## License

MIT 