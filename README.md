# CI/CD Practice with GitHub Actions

This project demonstrates a simple CI/CD pipeline for a static HTML site using GitHub Actions.

## Project Structure
- `index.html`: The main HTML file for the site.
- `.github/workflows/main.yml`: The GitHub Actions workflow file that automates validation and deployment.

## Workflow Features
- **Code Checkout**: Clones the repository for each workflow run.
- **File Listing**: Lists all files in the repository for verification.
- **HTML Validation**: Checks the HTML file for syntax and standards compliance using `html5validator`.
- **Deployment**: Publishes the site to GitHub Pages automatically on every push or pull request to the `main` branch.

## How to Use
1. Clone or fork this repository.
2. Push changes to the `main` branch to trigger the workflow.
3. View workflow results in the GitHub Actions tab.
4. The site will be deployed to GitHub Pages after a successful run.

## License
This project is for educational purposes.
