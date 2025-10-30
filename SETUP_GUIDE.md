# Data Visualization and Design Course - Setup Complete! 🎉

## What Has Been Set Up

Your `data-viz-design` course folder has been created with the following structure:

```
data-viz-design/
├── _quarto.yml           # Main Quarto configuration
├── README.md             # Repository documentation
├── .gitignore           # Git ignore rules
├── data-viz-design.Rproj   # RStudio project file
├── install.R            # R package installation script
├── postBuild            # Binder configuration
├── runtime.txt          # R version specification
│
├── about/               # Course information pages
│   ├── index.qmd       # Course home page
│   ├── overview.qmd    # Course overview
│   ├── syllabus.qmd    # Course syllabus
│   └── schedule_table.md
│
├── chapters/            # Course content (7 chapters)
│   ├── chapter1/       # Introduction to Data Visualization
│   ├── chapter2/       # Grammar of Graphics
│   ├── chapter3/       # Visualizing Distributions
│   ├── chapter4/       # Visualizing Relationships
│   ├── chapter5/       # Customizing Plots
│   ├── chapter6/       # Interactive Visualizations
│   └── chapter7/       # Advanced Topics
│
├── exercises/           # Student exercises
│   └── README.md
│
├── resources/           # Course resources
│   └── resources.md    # Links to books, tutorials, tools
│
└── assets/              # Styling and images
    ├── styles.css      # Custom CSS theme
    └── images/         # Course logo and images
```

## Next Steps

### 1. Customize Course Information

- [ ] Update `README.md` with your GitHub username
- [ ] Edit `about/overview.qmd` with specific course details
- [ ] Fill in `about/schedule_table.md` with actual dates
- [ ] Update `_quarto.yml` with correct GitHub repository URL
- [ ] Add your course logo to `assets/images/course_logo.png`

### 2. Develop Content

- [ ] Create slide content in each chapter's `slides/` folder
- [ ] Add exercises for each chapter
- [ ] Include example datasets in a `data/` folder (if needed)
- [ ] Add additional resources and readings

### 3. Build and Test

```bash
# Preview the website locally
quarto preview

# Render the full website
quarto render
```

### 4. Set Up GitHub Repository

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Make initial commit
git commit -m "Initial course setup"

# Add remote and push
git remote add origin https://github.com/YOUR-USERNAME/data-viz-design.git
git branch -M main
git push -u origin main
```

### 5. Deploy to GitHub Pages

```bash
# Publish to GitHub Pages
quarto publish gh-pages
```

### 6. Set Up Binder (Optional)

1. Push your repository to GitHub
2. Go to https://mybinder.org
3. Enter your repository URL
4. Copy the badge markdown and update README.md

## Customization Tips

### Packages
The `install.R` file currently includes:
- tidyverse
- ggplot2
- plotly
- patchwork

Add more packages as needed for your course.

### Theme
The website uses the "lux" theme with custom styles in `assets/styles.css`.
You can change the theme in `_quarto.yml` under `format: html: theme:`.

### Chapter Topics
The current 7 chapters are templates. Feel free to:
- Rename chapters
- Add or remove chapters
- Modify learning objectives
- Update the chapter list in `_quarto.yml`

## Resources Included

The `resources/resources.md` file contains links to:
- ggplot2 documentation and tutorials
- Data visualization books
- Color tools
- R community resources

## Questions?

Refer to:
- [Quarto Documentation](https://quarto.org/)
- [ggplot2 Documentation](https://ggplot2.tidyverse.org/)
- The original `introduction_to_R` course for examples

Happy teaching! 🎓📊
