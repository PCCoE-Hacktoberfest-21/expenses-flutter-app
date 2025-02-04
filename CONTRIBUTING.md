## Contribution Guidelines

- Select an issue and ask to be _assigned_ to it.
- **Star** the repository.
- On the [GitHub page for this repository](https://github.com/PCCoE-Hacktoberfest-21/expenses-flutter-app), click on the Button "**Fork**".
  ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)
- Create clone **_your forked repository_** on your local machine.
  ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

  For example, run this command inside your terminal:

  ```bash
  git clone https://github.com/<your-github-username>/FRIDAY.git
  ```

  **Replace \<your-github-username\>!**

  Learn more about [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning a repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

- Before you make any changes, [keep your fork in sync](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) to avoid merge conflicts:

  ```bash
  git remote add upstream https://github.com/PCCoE-Hacktoberfest-21/expenses-flutter-app.git
  git fetch upstream
  git pull upstream master
  git push
  ```

- If you run into a **merge conflict**, you have to resolve the conflict. There are a lot of guides online, or you can try this one by [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

- Checkout to development branch (_name your branch according to the issue name_).

  ```bash
  git checkout -b <branch-name>
  ```

- Write your code in the Python file.
- Add the changes with `git add`, `git commit` ([write a good commit message](https://chris.beams.io/posts/git-commit/), if possible):

  ```bash
  git add -A
  git commit -m "<your message>"
  ```

- Push the code _to your repository_.

  ```bash
  git push origin <branch-name>
  ```

- Go to the GitHub page of _your fork_, and **make a pull request**:

  ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

  Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

- Now wait, until one of us _reviews your Pull Request_! If there are any conflicts, you will get a notification.
