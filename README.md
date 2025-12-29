# Abdomen CT Studies Review Dataset

Interactive visualization of public abdomen CT datasets for medical imaging research.

## Features

- **Dataset Overview**: Statistics and trends of 45+ CT datasets
- **Organ Analysis**: Breakdown by annotated organs
- **Bias Evaluation**: Ethics and bias assessment metrics
- **Interactive Tables**: Search and filter capabilities
- **Visualizations**: Charts for publication trends and organ distribution

## Setup on GitHub Pages

1. **Create a new repository** on GitHub
2. **Upload these files**:
   - `index.html`
   - `data.json`
   - `README.md`
3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
   - Click Save
4. **Access your site** at: `https://yourusername.github.io/repo-name/`

## Data Structure

### Datasets Features
45 datasets with:
- Publication details (year, journal, citations)
- CT study counts (public/private)
- Clinical metadata (phases, device, location)
- Annotated organs
- Licensing information

### Organ-Level Analysis
Detailed organ segmentation data across datasets

### Bias Evaluation
Assessment of:
- Ethics approval and pseudonymization
- Commercial use permissions
- Demographic representation
- Technical and labeling bias

## Technologies

- Pure HTML/CSS/JavaScript (no build required)
- Chart.js for visualizations
- Responsive design for mobile/desktop

## License

Data sourced from published medical imaging datasets. Please cite original papers when using this data.
