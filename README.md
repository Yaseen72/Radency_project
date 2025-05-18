# Citizens Bank Website

A responsive website for Citizens Bank built with HTML, CSS, SASS/SCSS, and JavaScript.

## Features

- Fully responsive design using custom media queries
- Mobile-first approach
- Custom grid system (no external frameworks)
- Component-based architecture
- Modular SASS structure
- Interactive elements with JavaScript

## Project Structure

```
project/
├── css/
│   └── main.css (compiled from SCSS)
├── img/
│   ├── citizens-logo.png
│   ├── hero-image.jpg
│   └── team-member-*.jpg
├── js/
│   └── main.js
├── scss/
│   ├── abstracts/
│   │   ├── _functions.scss
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   ├── base/
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _utilities.scss
│   ├── components/
│   │   ├── _advantage-card.scss
│   │   ├── _buttons.scss
│   │   ├── _hero.scss
│   │   ├── _social-links.scss
│   │   └── _team-member.scss
│   ├── layout/
│   │   ├── _footer.scss
│   │   ├── _grid.scss
│   │   ├── _header.scss
│   │   └── _navigation.scss
│   └── main.scss
├── index.html
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js and npm

### Installation

1. Clone the repository
2. Install dependencies:
```
npm install
```

### Development

To compile SASS to CSS once:
```
npm run sass
```

To watch for changes and compile automatically:
```
npm run sass:watch
```

### Production

To build for production (compressed CSS):
```
npm run build
```

## Responsive Breakpoints

- Extra small: 375px
- Small: 576px
- Medium: 768px
- Large: 992px
- Extra large: 1200px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- IE11 (limited support) 