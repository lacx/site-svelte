# site-svelte

### Create Svelte Project

 1 - Created new project from gitkraken (Readme.md, License.md only)

 2 - Initialize New Codespace from GitHub.com 

 3 - Create a Svelte project with vite in GitHub Codespaces

```bash
npm init vite
```
- installs create-vite@4.4.1 (y)
- set project name (site-vite-project)
- select Svelte, JavaScript (project is created)
```bash
cd site-vite-project
npm install
npm run dev
```

### Create GitHub Action to deploy the site to GitHub Pages

- In the GitHub repo go to _Settings/Pages_ at _Source_ select __GitHub Actions__ and click _create your own_

- see the file _.github\workflows\deploy-to-gh-pages_