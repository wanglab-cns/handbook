# Welcome to the Wang lab handbook

The following is a guide for new and existing members of the Wang Lab at Princess Margaret Hospital. It provides essential information about lab policies, procedures, and resources to help you navigate your time in the lab effectively.

Below is information about updating the handbook.

# Setting up the handbook
The handbook is hosted on [GitHub](https://github.com/wanglab-cns/handbook) and can be accessed at [https://wanglab-cns.github.io/handbook/](https://wanglab-cns.github.io/handbook/). The handbook is built using [MkDocs](https://www.mkdocs.org/) and uses the readthedocs theme. The source files for the handbook are written in Markdown and are located in the `docs` directory of the repository. It is recommended you read the [getting started guide](https://www.mkdocs.org/getting-started/) for MkDocs to familiarize yourself with the tool and its features.

## Running locally

To run the handbook locally, you will need to have Python and MkDocs installed. You can install MkDocs using pip:

```bash
pip install mkdocs
```

In your terminal, download the handbook repository and navigate to the root directory of the repository

```bash
git clone git@github.com:wanglab-cns/handbook.git
cd handbook
```

Please ensure you have the necessary permissions to access the repository. If you encounter any issues, please contact a labmate or the lab manager for assistance.

To serve the handbook locally, navigate to the root directory of the repository and run:

```bash
mkdocs serve
```

The handbook will be available at `http://localhost:8000/` in your web browser.

## Adding content
Content for the handbook is written in Markdown and stored in the `docs` directory. Each Markdown file corresponds to a page in the handbook. You can create new pages by adding new Markdown files to the `docs` directory and updating the `mkdocs.yml` configuration file to include them in the navigation.

See existing pages in the `docs` directory for examples of how to structure your content. You can also refer to the [Markdown guide](https://www.markdownguide.org/) or the [MkDocs documentation](https://www.mkdocs.org/) for information on how to format your content.

### Create a github branch
We recommend adding a new branch for your changes to keep the main branch stable. 

First, make sure you are on the main branch and have the latest changes:

```bash
git checkout main
git pull origin main
```

You can create a new branch using the following command:

```bash
git checkout -b feature/<branch-name>
```

Then, make necessary changes and commits. Then, push your branch to the remote repository:

```bash
git push origin feature/<branch-name>
```

Finally, create a pull request on GitHub to merge your changes into the main branch. Please ensure that your changes are reviewed and approved by a lab member before merging.

Once your changes are merged into the main branch, the handbook will be automatically built and deployed to GitHub Pages. Switch back to the main branch and pull the latest changes to keep your local repository up to date:

```bash
git checkout main
git pull origin main
```

*NOTE*: The handbook uses GitHub actions to automatically build and deploy the handbook to GitHub Pages whenever changes are pushed to the main branch. Therefore, it is important to ensure that your changes are thoroughly reviewed and tested before merging them into the main branch.