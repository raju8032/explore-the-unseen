# Uneen Explorer

A platform where locals share their favorite spots with photos, stories, and personal context. Travelers get access to these authentic experiences—curated to their preferences by AI.

## Features

- **Local Guides**: Create and share personalized mini-guides with photos and tips
- **AI Recommendations**: Get personalized suggestions based on your preferences and community feedback
- **Social Features**: Follow guides, bookmark spots, plan trips, comment, and share experiences
- **Interactive Maps**: Browse locations and create custom itineraries
- **Community**: Connect with fellow travelers and locals

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Adding Background Images

Replace the placeholder images in `public/images/` with your actual images:
- `hero.jpg` - Wide waterfall image with turquoise pool
- `waterfall-close.jpg` - Close-up waterfall image with dark rocks

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **State Management**: React hooks with localStorage

## Project Structure

```
src/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── Hero.tsx
│   ├── Idea.tsx
│   ├── Features.tsx
│   ├── HowItWorks.tsx
│   ├── Guides.tsx
│   ├── MapSection.tsx
│   └── Community.tsx
public/
└── images/
    ├── hero.jpg
    └── waterfall-close.jpg
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.
