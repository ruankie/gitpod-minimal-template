[![GitHub Repo stars](https://img.shields.io/github/stars/ruankie/conda-py-minimal-template)](https://github.com/ruankie/gitpod-minimal-template)
[![GitHub file size in bytes](https://img.shields.io/github/size/ruankie/conda-py-minimal-template)](https://github.com/ruankie/gitpod-minimal-template)

# gitpod-minimal-template
Minimal template with the essentials for quickly setting up new python projects on [Gitpod](https://gitpod.io/). It includes a simple folder structure and a conda environment for isolated dependency management.

## Usage
1. Start a new repo using this template.
2. Open up this repo in Gitpod by going to `https://gitpod.io/#/<your-repo-url>`

    > **Notes:** 
    > 1. *Your conda environment and its dependencies should automatically be installed according to the setup inside the `.gitpod.yml` file.* 
    > 2. *Whenever you update your conda dependencies inside the `conda.yml` file, you might have to open a new Gitpod workspace by navigating to the url above.*

3. Update your `LICENSE` file.
4. Update your `README.md` file.
5. Add your own scripts in `./src/`
6. Add your own notebooks in `./notebooks/`
7. Add your own data in `./data/`

This template creates the following folder structure:

```
<your-repo-name>
├── LICENSE
├── README.md
├── conda.yml
├── data
├── notebooks
│   └── example.ipynb
├── setup.py
└── src
    ├── __init__.py
    └── utils.py
```
