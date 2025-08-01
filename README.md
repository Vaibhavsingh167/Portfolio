<!DOCTYPE html>
# Vaibhav Singh Portfolio Website

Welcome to the source code for my personal portfolio website! This single-page site showcases my skills, projects, and background.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Demo

A live demo is available at: [https://your-domain.com](https://your-domain.com)

## Features

- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile.
- **Dark/Light Mode**: Toggle between themes with a click.
- **Smooth Scrolling**: Navigate sections smoothly.
- **Projects Showcase**: Highlight key web and algorithm projects.
- **Contact Form**: Email form integration via `mailto:`.

## Technologies Used

- **HTML5** for semantic markup
- **CSS3** for modern styling, grid and flex layouts
- **JavaScript** for interactive features (theme toggle, smooth scroll)


## Getting Started

Follow these steps to run the project locally.

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari).
- Optional: A local HTTP server (e.g., Live Server in VSCode) for testing.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vaibhav/portfolio.git
   cd portfolio
   ```
2. **Open `index.html`** in your browser, or start your local server:
   ```bash
   # Using Python 3.x
   python -m http.server 8000

   # Open http://localhost:8000 in your browser
   ```

## Configuration

- **Profile Image**: Replace the placeholder at `#about img` with your own image in the `images/` folder.
- **Contact Email**: Update the `action` attribute in the contact form to your email address.
- **Social Links**: Edit the GitHub/LinkedIn URLs in the footer.

## Project Structure

```
portfolio/
├── index.html       # Main single-page layout
├── css/
│   └── style.css    # All styling rules
├── js/
│   └── main.js      # JavaScript for theme toggle
├── images/          # Placeholder images and your own assets
└── README.md        # This file
```

## Customization

- Add or remove sections by editing the `<section>` blocks in `index.html`.
- Tweak colors, typography, or layout details in `css/style.css`.
- Enhance interactivity by expanding `js/main.js` (e.g., add smooth-scroll).

## Deployment

You can deploy easily using GitHub Pages, Netlify, Vercel, or any static hosting.

### GitHub Pages
1. Push your code to `main` branch on GitHub.
2. In repository settings, enable GitHub Pages from `main` branch.

## Contributing

Contributions are welcome! Create an issue or pull request for any improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file.

## Contact

- **Email**: vaibhav@example.com
- **GitHub**: [github.com/vaibhav](https://github.com/vaibhav)
- **LinkedIn**: [linkedin.com/in/vaibhav](https://linkedin.com/in/vaibhav)

---

Thanks for checking out my portfolio! 🎉
