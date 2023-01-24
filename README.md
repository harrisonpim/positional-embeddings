# 🔢 Positional embeddings

The code in this repo is used top create the results and visualisations for the blog post: [Understanding positional embeddings in transformer models](https://harrisonpim.com/blog)

## 🚀 Getting started

### Running with devcontainers

This project uses [vscode devcontainers](https://code.visualstudio.com/docs/remote/containers) to maximise its reproducibility.

To recreate the project with devcontainers, you'll need: 
- [Docker](https://www.docker.com/) 
- [VS Code](https://code.visualstudio.com/) 
  - with the [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.

1. Clone the repo
2. Open the repo in VS Code
3. Click the "Reopen in Container" button in the bottom right of the window
4. Open the [first notebook](notebooks/positional-embeddings.ipynb) in the `notebooks` folder

### Running without devcontainers

If you don't want to use devcontainers, you can still run the notebook(s) locally by installing the dependencies in `.devcontainer/requirements.txt` and running `jupyter notebook` in the root of the repository.
