# AI-assisted Content Creator Platform

A comprehensive web application for content creators to streamline their workflow and optimize content for YouTube, TikTok, Instagram, and other platforms using AI tools.

## Features

- **AI-Powered Content Ideation**: Generate creative content ideas based on trends, keywords, and audience preferences
- **Script Generation**: Create tailored scripts for different content formats and platforms
- **Editing Assistance**: Get AI suggestions for improving content quality and engagement
- **Multi-Platform Optimization**: Automatically format content for different platforms' requirements
- **Performance Tracking**: Monitor engagement metrics across platforms in a unified dashboard
- **Monetization Analysis**: Track revenue streams and identify new monetization opportunities

## Tech Stack

- **Frontend**: React.js with Next.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **AI Integration**: OpenAI API
- **Media Processing**: FFmpeg
- **Authentication**: OAuth 2.0 with social platform integrations
- **Cloud Storage**: AWS S3

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MongoDB instance
- OpenAI API key
- Social media developer accounts for API integration

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/dxaginfo/ai-content-creator-platform.git
   cd ai-content-creator-platform
   ```

2. Install dependencies
   ```bash
   # Install root dependencies
   npm install
   
   # Install frontend dependencies
   cd client
   npm install
   
   # Install backend dependencies
   cd ../server
   npm install
   ```

3. Set up environment variables (see documentation for required variables)

4. Start development servers
   ```bash
   # Start backend server
   cd server
   npm run dev
   
   # Start frontend server
   cd ../client
   npm run dev
   ```

## Project Structure

```
ai-content-creator-platform/
├── client/                 # Frontend React application
│   ├── public/             # Static assets
│   └── src/                # React source files
│       ├── components/     # Reusable components
│       ├── contexts/       # React contexts for state management
│       ├── hooks/          # Custom React hooks
│       ├── pages/          # Next.js pages
│       ├── services/       # API service functions
│       └── styles/         # CSS/SCSS styles
├── server/                 # Backend Express application
│   ├── src/                # Server source files
│   │   ├── controllers/    # Request handlers
│   │   ├── middleware/     # Express middlewares
│   │   ├── models/         # Database models
│   │   ├── routes/         # API routes
│   │   ├── services/       # Business logic services
│   │   └── utils/          # Utility functions
│   └── tests/              # Server tests
├── .github/                # GitHub workflows
├── docs/                   # Documentation files
└── shared/                 # Shared code between client and server
```

## Target Market

- Content creators (YouTube, TikTok, Instagram)
- Influencers and social media personalities
- Marketing professionals
- Digital content agencies

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Built as part of the AI Web App Ideas Database initiative
- Developed using Den AI-powered development workflow