# Getting Started

This repository is a [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/) template for a project using [ship-it](https://github.com/rajasoun/ship-it) and [TypeScript](https://www.typescriptlang.org/). 


```sh
cookiecutter https://github.com/rajasoun/cookiecutter-ship-it
```

Once finished, navigate into your new project folder :

```sh
cd <project_name>
```

Refer README.md in the created project

1.  To enable husky, commitzen, commitlint, prettier and lint-staged

    ```
    npm install
    ```

1.  To enable pre-commit (python based) and ggshield

    ```
    pip3 install pipenv
    pipenv shell
    pipenv install
    ```

1.  Populate .env file with GITHUB_TOKEN, GITGUARDIAN_API_KEY and GITGUARDIAN_API_URL
    ```
    cp .env.sample .env
    ```

1. husky, commitzen, commitlint, prettier, lint-staged and ggshield will kick in

    ```
    git init
    git add -A
    git commit
    ```
