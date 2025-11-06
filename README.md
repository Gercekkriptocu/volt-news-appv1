# VOLT - Turkish Crypto News Aggregator

A Turkish-focused crypto news aggregator built with Next.js, featuring real-time updates, Telegram integration, and a retro Windows XP theme.

## Features

- 🌍 Dual-language support (Turkish & English)
- 📰 Real-time crypto news from multiple sources
- 💬 Telegram bot integration for automatic news sharing
- 🎨 Retro Windows XP design with draggable elements
- 📊 Live crypto price ticker
- 🔄 Infinite scroll and pull-to-refresh
- 📱 Fully responsive mobile design

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Scraping**: Cheerio
- **APIs**: Tree of Alpha, Bloomberg, Exa, OpenAI, Telegram
- **Deployment**: Vercel

## Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/volt-news-app.git

# Navigate to the project directory
cd volt-news-app

# Install dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the app.

## Configuration

### Telegram Bot

Update the Telegram bot token and channel ID in:
- `src/app/api/telegram/auto-share/route.ts`

### API Keys

API keys are already configured in the code:
- **Exa API**: `src/exa-api.ts`
- **OpenAI API**: `src/openai-api.ts`
- **0x API**: `src/0x-api.ts`

## Deployment

Deploy to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/volt-news-app)

## License

MIT License - feel free to use this project for your own purposes.

## Credits

Built with ❤️ using Ohara AI Platform
