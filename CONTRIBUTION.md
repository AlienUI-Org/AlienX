# Contributing to AlienX

Thank you for considering contributing to **AlienX**! Your contributions play a vital role in building a cutting-edge Vs Code Extension. This guide outlines how to get started and ensures a seamless contribution process for everyone involved.

## Getting Started

1. **Fork the repository.**
2. **Clone your fork to your local machine:**

   - Clone your fork to your local machine using the following command (replace `<your-username>` and `<repository>`
     with your GitHub username and the repository name):

   ```bash
   git clone https://github.com/<your-username>/<repository>.git
   ```

3. **Add the Original Repository as a Remote:**

   - Change into the directory of your cloned repository:

   ```bash
   cd <repository>
   ```

   - Add the original repository as a remote (this helps you fetch changes from the original repository):

   ```bash
   git remote add upstream https://github.com/<original-owner>/<repository>.git
   ```

4. **Create a Branch:**

   - Create a new branch for your contribution (replace `<branch-name>` with a meaningful name):

   ```bash
   git checkout -b <branch-name>
   ```

5. **Make Changes :**
   - Pick a task or feature you'd like to work on. Check out the [Issues](https://github.com/AlienUI-Org/AlienX/issues) tab for open task.
   - Fix or build the task assigned to you on the `issues` tab, and then attach an image or recorded video to the Pull request (PR) you made.
6. **Committing Changes**

   ```bash
   git add .
   git commit -m "Add your descriptive commit message here"
   ```

7. **Fetch and Rebase from Upstream:**

   - Before pushing your changes, fetch the latest changes from the original repository and rebase your branch:

   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

   - Resolve any merge conflicts if they occur.

8. **Push your changes to your fork:**

   - Push your changes to your fork on GitHub:

   ```bash
   git push origin <branch-name>
   ```

9. **Open a Pull Request (PR):**
   - Visit your fork on GitHub and switch to the branch you just pushed.
   - Click on the "New Pull Request" button.
   - Provide a clear and descriptive title and rendered image or recorded video for your PR.
   - Explain the purpose of your changes in the PR description.

## Pull Request Guidelines

- Ensure your code follows the project's coding standards.
- Be responsive to feedback and make necessary adjustments.

## Code of Conduct

- Review and adhere to our [Code of Conduct](https://github.com/AlienUI-Org/AlienX/blob/main/CODE%20OF%20CONDUCT.md) during your contribution.

## Show Your Support

If you love AlienX, consider giving the repository a ⭐ on GitHub! It motivates us to keep improving and building the extension.
**How to give the repository a star:**

- Navigate to the top of the AlienX repository.
- Click on the "Star" button in the upper right corner of the page.

Thank you for being a part of AlienX! 👽
