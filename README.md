# 🎄 Christmas Tree

An interactive 3D Christmas tree built with React, TypeScript, and Three.js. Features AI-powered hand gesture recognition for interactive ornament placement using TensorFlow.js and hand pose detection.

## Features

- 🎨 Interactive 3D Christmas tree visualization with Three.js
- 🤖 AI-powered hand gesture recognition using TensorFlow.js
- 🎁 Dynamic ornament placement and animation
- ❄️ Animated snow effects
- ✨ Spiral lights with realistic lighting
- 🌟 Interactive top star
- 📱 Gesture-based controls via webcam

## Tech Stack

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Three.js** - 3D graphics
- **@react-three/fiber** - React renderer for Three.js
- **@react-three/drei** - Useful helpers for React Three Fiber
- **TensorFlow.js** - Machine learning
- **@tensorflow-models/handpose** - Hand pose detection
- **Vite** - Build tool

## Prerequisites

- Node.js 16+
- npm or yarn

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd christmas-tree
   ```

2. Install dependencies:
   ```bash
   npm install --legacy-peer-deps
   ```

## Development

Run the development server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or the next available port).

## Build

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Project Structure

```
├── components/           # React components
│   ├── Experience.tsx    # Main Three.js scene
│   ├── Foliage.tsx       # Tree foliage
│   ├── SpiralLights.tsx  # Light animation
│   ├── Ornaments.tsx     # Ornament management
│   ├── Snow.tsx          # Snow effect
│   ├── TopStar.tsx       # Tree top star
│   ├── GestureController.tsx  # Hand gesture recognition
│   └── DeveloperPanel.tsx # Debug panel
├── utils/               # Utility functions
│   ├── math.ts          # Math helpers
│   └── defaults.ts      # Default configurations
├── public/              # Static assets
│   └── models/          # 3D models
└── App.tsx              # Main app component
```

## Usage

1. Allow camera access when prompted
2. Position your hand in front of the camera
3. Use hand gestures to interact with the Christmas tree
4. Watch as the tree animates and responds to your movements

## License

This project is provided as-is.
