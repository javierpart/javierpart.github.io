# 👋 Hello! This is my personal web page repo!

Here you can find the source code of my [personal web page](https://javierpart.github.io.).

## 📜 Table of Contents
- [👋 Hello! This is my personal web page repo!](#-hello-this-is-my-personal-web-page-repo)
  - [📜 Table of Contents](#-table-of-contents)
- [👷 Working on this project](#-working-on-this-project)
  - [🏗️ Development](#️-development)
  - [📦 Building and deploying](#-building-and-deploying)

# 👷 Working on this project

## 🏗️ Development

¿Do you want to **copy this landing page and use it on your own**? If you have **[Docker](https://www.docker.com/) and [VS Code](https://code.visualstudio.com/) installed** then is so simple with **[VS Code devcontainers](https://code.visualstudio.com/docs/remote/containers)**! 🎉

1. Open **[VS Code](https://code.visualstudio.com/)**

2. Install **[remote containers plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)** in vscode.
    ```
    1. Press `Ctrl+P`
    2. Paste `ext install ms-vscode-remote.remote-containers`
    3. Press `Enter`
    ```

3. Run the **development container** *(wait, first time takes some time to run)*:
    ```
    1. Press `Ctrl+Shift+P`
    2. Type `rebuild and reopen in container`
    3. Press `Enter` 
    ```

Then you can just use the **vs code integrated terminal** (*Press ``Ctrl+` ``*) to start your building server:

```
mkdocs new .
mkdocs serve
```

## 📦 Building and deploying

This process is **automatically performed thanks to [github actions](https://squidfunk.github.io/mkdocs-material/publishing-your-site/#with-github-actions)**. 👉 After merging, or pushing, to the `main` branch (*you should never push directly to the main branch* 😅) this project is built and pushed into the `gh-pages` branch **with the last changes**. If you [configure github pages in this repo to look into the gh-pages branch](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) then you will have a fully updated and automated landing page for you! 🤯