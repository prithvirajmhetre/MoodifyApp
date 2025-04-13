# Mood-based Playlist & Quote Generator

A web application that generates personalized music playlists and inspirational quotes based on your current mood using OpenAI's API. This application provides a seamless, interactive experience for discovering music and motivation tailored to how you feel.

![Mood-based Playlist & Quote Generator](https://i.imgur.com/JvULq7c.png)

## Features

- **Mood Selection**: Choose from various mood options (Happy, Sad, Energetic, Calm, Focused, Romantic, etc.)
- **AI-Generated Content**: Uses OpenAI API to create personalized quotes and music recommendations
- **Interactive Music Player**: Fully-featured player with controls for play/pause, next/previous, and progress tracking
- **Beautiful Animations**: Smooth transitions and micro-interactions enhance the user experience
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Fallback System**: Gracefully handles API limits with engaging mock content and clear notifications

## Technology Stack

- **Frontend**: React with TypeScript and Framer Motion for animations
- **UI Framework**: Tailwind CSS with ShadCN UI components
- **Backend**: Node.js with Express
- **AI Integration**: OpenAI API
- **State Management**: React Query for data fetching and cache management

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- An OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd mood-playlist-generator
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5000](http://localhost:5000) in your browser to see the application.

### Configuration

You can customize various aspects of the application:

- **Theme Colors**: Modify the `theme.json` file to change the application's color scheme
- **Available Moods**: Edit the moods array in `shared/schema.ts` to customize the mood options
- **OpenAI Parameters**: Adjust the parameters in `server/openai.ts` to change the style of generated content

## Usage

1. Select a mood that best represents how you're feeling
2. Wait a moment while the application generates personalized content
3. Explore your custom playlist and inspirational quote
4. Interact with the music player to listen to recommended tracks
5. Click the refresh buttons to generate new content for the same mood
6. Select "Choose Another Mood" to start over

## API Integration

The application uses OpenAI's GPT-4o model to:

1. Generate inspirational quotes tailored to your mood
2. Create personalized playlists with track details
3. Craft descriptive playlist names and descriptions

## Deployment

The application can be deployed using various platforms:

- **Replit**: Click the "Deploy" button in your Replit project
- **Vercel/Netlify**: Connect your repository for automatic deployments
- **Docker**: Use the included Dockerfile for containerized deployment

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- OpenAI for providing the AI capabilities
- ShadCN UI for the component library
- Framer Motion for animation utilities
- The open-source community for various libraries and tools
