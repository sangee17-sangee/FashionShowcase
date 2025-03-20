# Fashion Products Landing Page

A modern, responsive landing page for fashion products built with React, TypeScript, and Express. Features a sleek design with product showcases, newsletter subscription, and contact form functionality.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-first approach
- ✨ Animated UI components using Framer Motion
- 📝 Newsletter subscription form
- 📬 Contact form with validation
- 🛍️ Product showcase grid
- 🎯 Brand story section

## Tech Stack

- **Frontend:**
  - React
  - TypeScript
  - Tailwind CSS
  - shadcn/ui components
  - Framer Motion for animations
  - React Query for API integration

- **Backend:**
  - Express.js
  - TypeScript
  - Zod for validation
  - In-memory storage

## Getting Started

1. Clone the repository:
```bash
git clone <your-repo-url>
cd fashion-landing-page
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5000`.

## Project Structure

```
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   └── ui/
│   │   ├── pages/
│   │   ├── lib/
│   │   └── hooks/
├── server/
│   ├── routes.ts
│   ├── storage.ts
│   └── index.ts
└── shared/
    └── schema.ts
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run check` - Type check with TypeScript

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

MIT

## Acknowledgments

- Images from Unsplash
- UI Components from shadcn/ui
- Icons from Lucide React
