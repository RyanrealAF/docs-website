# Strategic and Forensic Document Repository

A static website serving a collection of strategic frameworks, case studies, and analytical documents, built with the "Dark Elegance" design system.

## Features

- **Dark Elegance Design System**: Professional dark theme with high contrast typography
- **Modular Architecture**: Collapsible content sections for focused reading
- **Responsive Design**: Mobile-first approach with semantic HTML5
- **Document Categories**: Organized sections for different types of content
- **Docker Support**: Containerized deployment with Nginx

## Local Development

### Using Docker
1. Ensure Docker Desktop is running
2. Navigate to the project directory
3. Run: `docker-compose up --build`
4. Access at `http://localhost:8080`

### Direct Browser
Open `index.html` in your browser for static viewing.

## Deployment to GitHub Pages

1. Create a new public repository on GitHub
2. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin master
   ```
3. Go to repository Settings > Pages
4. Under "Source", select "Deploy from a branch"
5. Choose "master" branch and "/ (root)" folder
6. Save and wait for deployment (usually 1-2 minutes)
7. Your site will be available at `https://yourusername.github.io/your-repo-name/`

## Project Structure

```
docs-website/
├── index.html          # Main page
├── styles.css          # Dark Elegance styling
├── Dockerfile          # Docker configuration
├── docker-compose.yml  # Docker Compose setup
├── README.md           # This file
└── docs/               # Document files
    ├── *.pdf           # PDF documents
    └── *.docx          # Word documents
```

## Design System

This project implements the "Web Burner Manifesto" design system featuring:
- Dark color palette with bronze and beige accents
- Archivo Black, Fira Sans Condensed, and Inter fonts
- Collapsible module sections
- Semantic HTML structure
- Accessibility-focused interactions

## Technologies Used

- HTML5
- CSS3 (Custom Properties)
- Docker & Nginx
- Google Fonts

## License

© 2025 Document Repository. All rights reserved.