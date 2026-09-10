# GitHub Pages deployment

This project is ready for free deployment on GitHub Pages using GitHub Actions.

## Steps

1. Push the project to a GitHub repository.
2. In GitHub, open the repository.
3. Go to Settings > Pages.
4. Set Source to GitHub Actions.
5. Commit and push the workflow file.
6. The deployment workflow will run automatically on every push to the main branch.

## Workflow file

- .github/workflows/deploy.yml

## Result

Your website will be published at a GitHub Pages URL like:

https://<your-username>.github.io/<your-repository-name>/

If the repository is named with your username or a custom project name, GitHub will generate the final URL automatically.
