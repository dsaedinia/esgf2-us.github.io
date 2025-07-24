# Contributor's Guide

Contributions to the content are more than welcome - please see the instructions below to get started.

## How to deploy the site locally

1. Clone the repository (`git clone https://github.com/esgf2-us/esgf2-us.github.io.git`)`
2. Install the require packages (`conda env create -f environment.yml`)
3. Run the website from your command line (`myst start`), see more on the [myst website documentation](https://mystmd.org/guide/quickstart-myst-websites)

## How to change content
All of the content is written as Jupyter Notebooks or markdown files. Once you make changes to files in the repository (ex. `README.md`), you can do the following:
1. Make sure the file is in the table of contents (`_toc.yml`), if it is not, add it to the list of files
2. Render the website locally (see previous steps)
3. Commit your changes to github on your own fork of the project, creating a dedicated feature branch (see [git branches content here for more details](https://foundations.projectpythia.org/foundations/github/git-branches.html))

## How to write markdown documents
This website makes use of myst markdown - for a detailed guide on the required syntax, please see ["Working with MyST Markdown"](https://mystmd.org/guide/quickstart-myst-markdown)

## How to contribute to Github
Once you have changes you would like to make, please follow the workflow:
1. Fork the project repository at https://github.com/esgf2-us/esgf2-us.github.io
2. Clone the forked repository `git clone https://github.com/{USERNAME}/esgf2-us.github.io.git` where USERNAME is your own username
3. Create a new branch using `git checkout -b 'new-branch name'`
4. Make your changes, and add them `git add new_markdown_file.md`
5. Commit your changes `git commit -m "ADD: Add new file"`
6. Push your changes `git push`
7. Open a pull request on the web editor at https://github.com/esgf2-us/esgf2-us.github.io

A maintainer will follow up with your pull request and suggest changes or approve the contribution!

For more on Git/Github, please see the ["Getting Started with Github Guide"](https://foundations.projectpythia.org/foundations/getting-started-github)

