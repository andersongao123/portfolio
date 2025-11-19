# Anderson Gao Portfolio - Project Structure

## Overview
This portfolio website now uses a modular project system where the main portfolio shows image-based project cards that link to individual detailed project pages.

## File Structure
```
Portfolio Website Materials/
├── index.html                    # Main portfolio page
├── project-template.html         # Template for creating new project pages
├── lightning-classification.html # Lightning ML project details
├── blackjack-glasses.html       # Blackjack glasses project details
├── f1-prediction.html           # F1 prediction model project details
├── caffeine-regulator.html      # Caffeine regulator project details
├── fourier-research.html        # Fourier research project details
└── [image files...]             # Project images and assets
```

## How to Add New Projects

1. **Copy the template**: Start with `project-template.html`
2. **Rename**: Give it a descriptive filename (e.g., `new-project.html`)
3. **Customize**: Replace all placeholder text (marked with CAPS like PROJECT_TITLE)
4. **Add to main portfolio**: Update `index.html` to add a new project card in the projects-grid section

### Template Placeholders to Replace:
- `PROJECT_TITLE` - Name of your project
- `PROJECT_SUBTITLE` - Brief description
- `PROJECT_PERIOD` - Time period (e.g., "January 2025 - Present")
- `PROJECT_IMAGE` - Main project image filename
- `PROJECT_DESCRIPTION` - Detailed overview
- `FEATURE_X_TITLE` - Key feature titles
- `FEATURE_X_DESCRIPTION` - Key feature descriptions
- `TECH_X` - Technology tags
- `TECHNICAL_DETAILS_DESCRIPTION` - Technical implementation details
- `CHALLENGES_DESCRIPTION` - Challenges and solutions
- `RESULTS_DESCRIPTION` - Results and impact
- `GITHUB_LINK`, `DEMO_LINK`, `PAPER_LINK` - Project links

## Project Card Structure (Main Portfolio)
Each project card in the main portfolio follows this format:
```html
<a href="project-filename.html" class="project-card-link">
    <div class="project-card">
        <div class="project-image-container">
            <img src="project-image.png" alt="Project Name" class="project-preview-image">
            <div class="project-overlay">
                <div class="project-title">Project Name</div>
                <div class="project-period">Time Period</div>
            </div>
        </div>
    </div>
</a>
```

## Features
- **Scalable**: Easy to add new projects using the template
- **Consistent Design**: All project pages follow the same professional layout
- **Mobile Responsive**: Works well on all device sizes
- **Professional**: Clean, modern design suitable for engineering portfolios
- **Easy Maintenance**: Each project is a separate file for easy updates

## Customization Tips
- Use high-quality images (recommended: 800px+ width)
- Keep project titles concise but descriptive
- Use consistent time period formatting
- Include relevant technical tags for your field
- Update project links to point to actual repositories/demos when available
