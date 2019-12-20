Codio platform documentation


# How it works

The project is using [mkdocs]() to generate documentation from markdown files.

## Installing

1. Clone the repo to your Codio python based box or locally
1. install `mkdocs` [https://www.mkdocs.org/#installation](https://www.mkdocs.org/#installation)

    ```
    pip install mkdocs
    ```

## Developing

1. start development mode with `mkdocs serve -a 0.0.0.0:8000` command (If using Codio set up in .codio file - **Start mkdocs**)
1. Edit files and preview in your browser on port 8000 (If using Codio set up in .codio file - **Preview**)

## Deploying

Run `mkdocs gh-deploy` to deploy the documentation (If using Codio set up in .codio file - **Deploy Docs**)