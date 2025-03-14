# Binance Balance Tracker

A real-time Binance balance tracking application built with Next.js 13+, featuring WebSocket integration and a sleek dark-themed UI.

## Features

- 🔄 Real-time balance updates via WebSocket
- 🌐 REST API fallback with automatic retry
- 🎨 Modern dark theme UI with animations
- 📊 Multiple view modes (Table and Cards)
- 🔔 Visual feedback for balance changes
- 🔌 Connection status indicators
- 🔄 Automatic reconnection handling
- ⚡ Built with Next.js 13+ and TypeScript

## Prerequisites

- Node.js 18+ and npm
- Binance API Key and Secret
- Git

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Johnnywalkerzz/nextjs-binance-bot.git
cd nextjs-binance-bot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file in the root directory:
```env
BINANCE_API_KEY=your_api_key_here
BINANCE_API_SECRET=your_api_secret_here
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Environment Variables

- `BINANCE_API_KEY`: Your Binance API key
- `BINANCE_API_SECRET`: Your Binance API secret

## Tech Stack

- Next.js 13+
- TypeScript
- Tailwind CSS
- Framer Motion
- Binance API
- Server-Sent Events (SSE)

## Features

### Real-time Updates
- WebSocket connection for instant balance updates
- Automatic reconnection with exponential backoff
- Visual indicators for connection status

### Multiple Views
- Table View: Traditional layout with sortable columns
- Card View: Modern card-based layout with animations

### UI/UX
- Dark theme optimized for trading
- Smooth animations for balance changes
- Connection status indicators
- Loading states and error handling
- Responsive design

## Security

- API keys are stored securely in environment variables
- All API requests are made server-side
- No sensitive data exposed to the client

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
- Animations powered by [Framer Motion](https://www.framer.com/motion/)
- Data from [Binance API](https://binance-docs.github.io/apidocs/)