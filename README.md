# My Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js CI](https://github.com/Pouetpouets/my-portfolio-2020/workflows/Node.js%20CI/badge.svg)](https://github.com/Pouetpouets/my-portfolio-2020/actions)
[![Dependencies](https://img.shields.io/david/Pouetpouets/my-portfolio-2020.svg)](https://david-dm.org/Pouetpouets/my-portfolio-2020)

A modern, responsive portfolio website showcasing my professional work and skills.

[View Demo](https://my-portfolio-2020.vercel.app/) | [Report Bug](https://github.com/Pouetpouets/my-portfolio-2020/issues) | [Request Feature](https://github.com/Pouetpouets/my-portfolio-2020/issues)

![Portfolio Screenshot](public/screenshot.png)

## Features

### 🎨 Modern UI/UX
- Responsive design that adapts seamlessly to all devices
- Smooth animations and transitions
- Dark/Light mode toggle
- Intuitive navigation

### 💼 Project Showcase
- Filterable project grid
- Detailed project pages with images and descriptions
- Live demo links and source code access
- Technology stack highlights

### 🛠 Skills Section
- Interactive skill visualization
- Progress indicators for different technologies
- Categorized skill presentation
- Downloadable resume

### 📝 Blog Integration
- Markdown support for blog posts
- Category and tag filtering
- Search functionality
- Comment system

### 📬 Contact Features
- Form validation
- Email integration
- Social media links
- Professional inquiry handling

## Technologies Used

- HTML5/CSS3
- JavaScript (ES6+)
- React.js
- Node.js
- Express
- MongoDB
- Sass/SCSS
- Jest for testing
- GitHub Actions for CI/CD
- Vercel for deployment

## Setup and Installation

1. Clone the repository:
```bash
git clone git@github.com:Pouetpouets/my-portfolio-2020.git
```

2. Install dependencies:
```bash
cd my-portfolio-2020
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your values
```

4. Start the development server:
```bash
npm start
```

## Development

### Testing
```bash
# Run unit tests
npm test

# Run e2e tests
npm run test:e2e

# Check test coverage
npm run test:coverage
```

### Linting
```bash
# Run ESLint
npm run lint

# Fix ESLint errors
npm run lint:fix
```

### Building for Production
```bash
npm run build
```

## Project Structure

```
my-portfolio-2020/
├── public/              # Static files
├── src/                 # Source files
│   ├── components/      # Reusable components
│   ├── pages/          # Page components
│   ├── styles/         # SCSS styles
│   ├── utils/          # Utility functions
│   ├── hooks/          # Custom React hooks
│   ├── context/        # React context
│   └── services/       # API services
├── tests/              # Test files
├── docs/               # Documentation
└── .github/            # GitHub configurations
```


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
