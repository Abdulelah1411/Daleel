# DALEEL - AI Coaching Assistant

DALEEL is a comprehensive B2B web application designed to serve professional soccer clubs in the Saudi Pro League (RSL). It acts as an AI coaching assistant, providing player analytics, match simulation, and performance insights.

## Features

- **Home Dashboard**: Overview of team performance, player stats, upcoming matches, and notifications
- **League Management**: View and analyze league statistics and standings
- **Team Management**:
  - General team information and performance metrics
  - Squad list with detailed player statistics
  - Interactive team formation builder
  - Match simulation with AI-powered insights
- **Training & Development**: Track and manage training programs
- **Medical Center**: Monitor player health and injuries
- **Market Place**: Player transfer and scouting system
- **Club Management**: Administrative tools and reports
- **Multi-language Support**: English and Arabic
- **Dark/Light Mode**: Customizable UI theme

## Tech Stack

- **Frontend**: Next.js 14, TypeScript, Tailwind CSS
- **UI Components**: Headless UI, Heroicons
- **State Management**: React Hooks
- **Database**: MySQL with Prisma ORM
- **AI Integration**: OpenAI API (coming soon)
- **Drag & Drop**: dnd kit

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd daleel
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` with your configuration.

4. Set up the database:
   ```bash
   npx prisma migrate dev
   ```

5. Run the development server:
   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
daleel/
├── src/
│   ├── app/                 # Next.js app router pages
│   ├── components/          # Reusable React components
│   │   ├── layout/         # Layout components
│   │   └── providers/      # Context providers
│   ├── lib/                # Utility functions and helpers
│   └── types/              # TypeScript type definitions
├── public/                 # Static assets
└── prisma/                # Database schema and migrations
```

## Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## License

This project is proprietary software. All rights reserved.

## Support

For support or inquiries, please contact [support@daleel.com](mailto:support@daleel.com)
