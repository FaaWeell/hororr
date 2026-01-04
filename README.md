```markdown
# Horror Interface

A horror-themed desktop game interface built with Next.js and Electron. Features a retro terminal aesthetic with creepy vibes.

## Tech Stack

- **Next.js 16** - React framework
- **Electron** - Desktop app wrapper
- **Tailwind CSS 4** - Styling
- **Zustand** - State management
- **Howler.js** - Audio/sound effects

## Getting Started

### Prerequisites

Make sure you have Node.js installed (v18 or higher recommended).

### Installation

```bash
# Clone the repo
git clone [https://github.com/FaaWell/contribution-ideas.git](https://github.com/FaaWell/hororr.git)
cd contribution-ideas

# Install dependencies
npm install

```

### Running the App

**Web version:**

```bash
npm run dev

```

Then open http://localhost:3000 in your browser.

**Desktop version (Electron):**

```bash
npm run electron:dev

```

### Building for Production

```bash
# Build desktop app
npm run electron:build

```

## Project Structure

```
contribution-ideas/
├── app/              # Next.js app router pages
├── components/       # React components
│   ├── Footer.tsx
│   ├── GameLayout.tsx
│   ├── Header.tsx
│   ├── MainScreen.tsx
│   └── Terminal.tsx
├── electron/         # Electron main process
├── hooks/            # Custom React hooks
├── lib/              # Utility functions
├── public/           # Static assets
├── store/            # Zustand state stores
└── types/            # TypeScript type definitions

```

## Contributing

Want to contribute? Here's how:

1. **Fork this repo** - Click the fork button up top
2. **Clone your fork**
```bash
git clone [https://github.com/FaaWeell/hororr.git](https://github.com/FaaWeell/hororr.git)

```


3. **Create a new branch**
```bash
git checkout -b feature/your-feature-name

```


4. **Make your changes** - Add new features, fix bugs, whatever you want
5. **Test your changes** - Make sure everything works
```bash
npm run dev
npm run lint

```


6. **Commit your changes**
```bash
git add .
git commit -m "Add: your feature description"

```


7. **Push to your fork**
```bash
git push origin feature/your-feature-name

```


8. **Open a Pull Request** - Go to the original repo and create a PR

### Contribution Ideas

Here are some high-level technical challenges designated for contributors (yes, you Megatron):

* [ ] **Spatial Audio Engine:** Implement a 3D positioning system using Web Audio API to create immersive, directional horror soundscapes.
* [ ] **Post-Processing Shader Pipeline:** Develop custom WebGL shaders to simulate realistic CRT monitor decay, chromatic aberration, and signal noise.
* [ ] **Psychological Horror AI:** Integrate a deterministic state machine that adapts jump-scare timing based on user inactivity or interaction patterns.
* [ ] **Terminal Hacking Subsystem:** Expand the terminal component into a fully functional shell environment with puzzle-solving mechanics and hidden directories.
* [ ] **Persistent State Architecture:** Engineer a robust save/load system using Electron's IPC (Inter-Process Communication) to serialize game state to the local file system.
* [ ] **Reactive Glitch System:** Create a global hook that randomly corrupts UI elements and text rendering based on the in-game "sanity" meter.
* [ ] **I18n Localization Layer:** Architect a scalable translation system to support multiple languages for global distribution.

### Code Style

* Use TypeScript
* Follow the existing code patterns
* Keep components small and focused
* Comment your code if it's doing something weird

## License

Do whatever you want with it. Just don't blame me if it gives you nightmares.

```

```
