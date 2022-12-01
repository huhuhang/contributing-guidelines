# How to Submit

Before submitting new labs, please read the [Collaborating with pull requests.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)

## Step 1: Create a new branch

1. Open your terminal
2. Navigate to your local repository
3.  Create a new branch with the following command:

    ```bash
    git checkout -b <branch-name>
    ```

    Replace `<branch-name>` with the name of your branch. For example:

    ```bash
    git checkout -b add-lab-hello-world
    ```

## Step 2: Add your changes

1. Open the file you want to edit
2. Make your changes
3. Save the file

## Step 3: Commit your changes

1. Open your terminal
2. Navigate to your local repository
3.  Add your changes with the following command:

    ```bash
    git add <file-name>
    ```

    Replace `<file-name>` with the name of the file you want to add. For example:

    ```bash
    git add python/add-lab-hello-world/step1.md
    ```

    You can also add all files with the following command:

    ```bash
    git add .
    ```
4.  Commit your changes with the following command:

    ```bash
     git commit -m "<commit-message>"
    ```

    Replace `<commit-message>` with a message that describes your changes. For example:

    ```bash
    git commit -m "Add lab-hello-world"
    ```

    You can learn more about [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
5.  Push your changes to GitHub with the following command:

    ```bash
    git push origin <branch-name>
    ```

    Replace `<branch-name>` with the name of your branch. For example:

    ```bash
    git push origin add-lab-hello-world
    ```

## Step 4: Create a pull request

1. Open your repository on GitHub.
2. Click **Pull requests**.
3. Click **New pull request**.
4. Click **compare across forks**.
5. Select the base branch: `master`
6. Select the head branch: `<branch-name>`
7. Click **Create pull request**.
8. Add a title and description for your pull request.

## Step 5: Wait for your pull request to be reviewed

1. Wait for your pull request to be reviewed.
2. Make any requested changes.
3. Push your changes to GitHub.
4. Wait for your pull request to be merged.
