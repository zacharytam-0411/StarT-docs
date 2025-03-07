# Contributing to this Wiki

## Before contributing
This is the offical and open-source wiki for the modpack Star Technology. Anyone can contribute to it, but, before you do, you need to know the ground rules:

1. Don't make troll submissions.
2. Don't make a new page in the wiki without asking the devs for permission.
3. Don't contribute anything that is the intelectual property of another party(such as images, diagrams, etc) without permission from the author of it.

## Useful references
- [What you can add to the wiki](https://squidfunk.github.io/mkdocs-material/reference/)

## Prerequisites
- [Git](https://git-scm.com/downloads) - Version Control System that will allow you to push the changes you make to the GitHub repository.
- [Visual Studio Code](https://code.visualstudio.com/download) - Code Editor integrated with Git with plenty of extensions to help you.
- [GitHub Account](https://github.com/) - Platform for hosting repositories, inl=cluding the repository for this wiki.
- [Python](https://www.python.org/downloads/) - Language that makes this wiki work.

## Preparing the workspace

1. Fork the [repository](https://github.com/trulyno/StarT-docs).
2. Open Visual Studio Code.
3. From the *Welcome* page, click on **Clone Git repository**, select **Clone from GitHub**, and select **YOUR_NAME/StarT-docs**.
4. Open new terminal from toolbar.
5. Run command the following commands:

    To create the enviroment:
    ```
    python -m venv venv
    ```
    To activate the enviroment:
     On Windows:
    ```
    .\venv\Scripts\activate
    ``` 
    On Mac:
    ```
    source venv/bin/activate
    ```
    To install [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/).
    ```
    pip install mkdocs-material
    ```

6. Run command to launch the app:
```
mkdocs serve
```
7. You can now make changes and it'll automatically update at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).
8. When you want to stop the app, go in the terminal and run Ctrl+C.
9. Commit your changes and open a pull request to the main repository.