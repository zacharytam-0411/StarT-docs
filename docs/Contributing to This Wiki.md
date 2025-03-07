# Contributing to this Wiki

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
7. You can now make changes and it'll automatically update at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
8. When you want to stop the app, go in the terminal and run Ctrl+C