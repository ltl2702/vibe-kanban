# Vibe Kanban

A project workspace containing a simple React TypeScript counter application built with Vite.

## Project Structure

```
vibe-kanban/
├── my-counter-app/          # React TypeScript counter application
│   ├── src/
│   │   ├── App.tsx         # Main counter component
│   │   ├── main.tsx        # Application entry point
│   │   └── ...
│   ├── package.json        # Dependencies and scripts
│   └── README.md          # Vite React template documentation
└── README.md              # This file
```

## Counter App Features

The `my-counter-app` is a simple React application that includes:
- **Counter Display**: Shows current count value
- **Increase Button**: Increments the counter by 1
- **Decrease Button**: Decrements the counter by 1
- Built with React 19.1.0, TypeScript, and Vite

## Getting Started

### Prerequisites
- Node.js (latest LTS version recommended)
- npm or yarn

### Installation & Usage

1. Navigate to the counter app directory:
   ```bash
   cd my-counter-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser to `http://localhost:5173` to view the app

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Technology Stack

- **React 19.1.0** - UI library
- **TypeScript** - Type-safe JavaScript
- **Vite** - Fast build tool and dev server
- **ESLint** - Code linting and formatting

## Future Enhancements

- Add reset button functionality (currently marked as TODO)
- Implement local storage persistence
- Add styling improvements
- Add unit tests

