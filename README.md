# Radadiya Prince Portfolio

Welcome to the Radadiya Prince video editing portfolio website! This project allows the owner to upload video edits without requiring a sign-in option. Uploaded edits are only visible to the owner and can be viewed by all users after refreshing the page.

## Features

- **Upload Area**: A dedicated section for the owner to upload video edits easily.
- **Gallery**: Displays uploaded video edits in a user-friendly grid format.
- **Motion Graphics**: Integrates motion graphics animations to enhance the visual appeal.
- **Animated Arrow**: Guides the owner to the upload section with an animated arrow.

## Project Structure

```
radadiya-prince-portfolio
├── src
│   ├── components
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   ├── UploadArea.tsx
│   │   ├── Gallery.tsx
│   │   ├── MotionGraphicsPlayer.tsx
│   │   └── AnimatedArrow.tsx
│   ├── pages
│   │   ├── index.tsx
│   │   └── upload.tsx
│   ├── styles
│   │   ├── globals.css
│   │   └── animations.css
│   ├── lib
│   │   └── storage.ts
│   ├── hooks
│   │   └── useUploads.ts
│   └── types
│       └── index.ts
├── api
│   └── upload.ts
├── public
│   └── animations
│       ├── arrow.json
│       └── motion-graphic.json
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/radadiya-prince-portfolio.git
   ```

2. Navigate to the project directory:
   ```
   cd radadiya-prince-portfolio
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm run dev
   ```

5. Open your browser and go to `http://localhost:3000` to view the website.

## Usage Guidelines

- The owner can upload video edits through the upload section.
- All users can view the uploaded edits after refreshing the page.
- The animated arrow will guide the owner to the upload area for easy access.

## License

This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.