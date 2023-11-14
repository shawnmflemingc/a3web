# Workflow for VS Code, GitHub and GIT.

Setting up Visual Studio Code (VSCode) for website design with GitHub in a team environment involves several key steps to ensure smooth collaboration and efficient workflow. Here's a guide to get you started:

## 1. Install Visual Studio Code (personal computer only)
- **Download and Install**: If not already installed, download and install VSCode from the [official website](https://code.visualstudio.com/).

## 2. Set Up Git and GitHub (personal computer only)
- **Install Git**: Make sure [Git](https://git-scm.com/) is installed on your system as VSCode uses Git for version control.
- **GitHub Account**: Each team member should have a GitHub account. Create one if needed.
- **Configure Git**: Set your username and email in Git, which is important for commit messages.

    ```command line
    git config --global user.name "Your Name"
    git config --global user.email "your_email@example.com"
    ```

## 3. Clone the Repository
- **Create/Select a Repository**: One team member should create a new repository on GitHub for the website project. Others should be added as collaborators.
- **Clone the Repository**: Use VSCode to clone the repository to your local machine.

    - Open VSCode
    - Go to the Source Control panel
    - Click on 'Clone Repository'
    - Enter the repository URL from GitHub
    - Choose a location on your local machine for the repo

### 4. Install Necessary Extensions
- **Live Server**: For a live preview of your website.
- **Prettier**: For code formatting.
- **ESLint**: For JavaScript linting.
- **GitLens**: Enhances Git capabilities in VSCode.

## 5. Branching Strategy (advanced)
For Geom101 we recommend everyone modifies `main` branch and not create different branches to avoid complexity. This means you and your team need to be clear where you make changes to not "step" on each other. 
- **Branches**: Use branches for different features or parts of the website. Typically, have a `main` branch, and create feature branches off it.
- **Naming Conventions**: Decide on a naming convention for branches (e.g., `feature/navbar`, `bugfix/footer-alignment`).

## 6. Workflow
- **Pull Before Work**: Always pull the latest changes from the main branch before starting new work.
- **Commit Often**: Make small, frequent commits with clear messages.
- **Push Regularly**: Push your changes to GitHub frequently.

## 7. Code Reviews and Merging
- **Pull Requests**: Use pull requests for merging changes to the `main` branch. This allows team members to review code.
- **Review Process**: Establish a review process. Each pull request should be reviewed by at least one other team member before merging (not required if everyone is using main).
- **Merge Conflicts**: Resolve merge conflicts promptly and carefully, preferably together to avoid errors.

## 8. Regular Communication
- **Meetings**: Schedule regular meetings to discuss progress, challenges, and plan ahead.
- **Communication Tools**: Use Microsoft Teams for daily communication.

## 9. Version Control Best Practices
- **Ignore Files**: Use a `.gitignore` file to exclude files that shouldn't be in the repository (like `node_modules`, build directories).
- **Commit Messages**: Write meaningful commit messages to explain what changes were made.

## 10. Backup and Security
- **Regular Backups**: Ensure that the code is backed up regularly (you can download the entire repository from GitHub).
- **Security**: Keep sensitive information like open Google API keys, usernames and passwords out of the repository.

By following these steps, your team can effectively use VSCode with GitHub for website design, ensuring a collaborative and efficient development process.
