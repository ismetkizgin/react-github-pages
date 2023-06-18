<h1  align="center">React of GitHub Pages Example</h1>
<p align="center">This is a sample repository created to demonstrate how to publish a project developed with React on the GitHub Pages platform.</p>


## Usage Instructions

1. Creating a React application.
2. Under the repository settings in GitHub, select GitHub Actions in the Pages section.
3. Add the `homepage` field to the `package.json` file. Without this field, the project won't be able to access the files correctly based on the URL. Example link: https://ismetkizgin.github.io/react-github-pages/
4. Add the <a href=".github/workflows/deploy-gh-pages.yml">deploy-gh-pages.yml</a> action to your project repository. After adding it, the deployment process will automatically occur after each commit pushed to the master branch.
