# MargDarshan

A modern, responsive learning platform built with React that provides AI-powered education and personalized learning paths.

## Features

- **Modern React Architecture**: Built with functional components and React hooks
- **Dark/Light Theme**: Toggle between dark and light modes with persistent preferences
- **Interactive AI Chatbot**: Real-time chat interface with LearnBot assistant
- **Course Roadmap**: Visual learning path with different skill levels
- **Responsive Design**: Mobile-first approach with modern CSS
- **Smooth Animations**: CSS animations and transitions for better UX

## Components

- `Header`: Navigation with theme toggle
- `Hero`: Landing section with call-to-action
- `Roadmap`: Course progression visualization
- `Chatbot`: Interactive AI assistant
- `Footer`: Site information and links

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## Project Structure

```
src/
├── components/
│   ├── Header.js & Header.css
│   ├── Hero.js & Hero.css
│   ├── Roadmap.js & Roadmap.css
│   ├── Chatbot.js & Chatbot.css
│   ├── Certification.js & Certification.css
│   ├── Feedback.js & Feedback.css
│   └── Footer.js & Footer.css
├── App.js
├── index.js
└── index.css
```

## Technologies Used

- **React 18**: Modern React with hooks
- **CSS3**: Custom CSS with CSS variables for theming
- **Font Awesome**: Icons and visual elements
- **Responsive Design**: Mobile-first CSS approach

## Features in Detail

### Theme System
- CSS custom properties for consistent theming
- Local storage persistence
- System preference detection
- Smooth transitions between themes

### Interactive Chatbot
- Real-time message handling
- Random response system
- Auto-scroll to latest messages
- Keyboard navigation support

### Form Handling
- Controlled components with React state
- Form validation
- Star rating system
- Form reset after submission

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License.

