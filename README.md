# Simplified_Radar_Digital_Twin

## Team Contribution Guidelines

Welcome to the project! All team members are encouraged to contribute new projects, features, improvements, and fixes. To keep the codebase organized and maintain code quality, everyone must follow the contribution workflow below.

### 1. Create a New Branch

Never work directly on the `main` branch. Create a separate branch for your project or feature.

First, clone the repository if you haven't already:

```bash
git clone <repository-url>
cd <repository-name>
```

Switch to the latest `main` branch:

```bash
git checkout main
git pull origin main
```

Create and switch to your own branch:

```bash
git checkout -b feature/your-feature-name
```

**Branch naming conventions:**

- `feature/feature-name` — New features or projects.
- `fix/issue-name` — Bug fixes.
- `docs/documentation-name` — Documentation changes.
- `refactor/change-name` — Code refactoring.

Example:

```bash
git checkout -b feature/radar-visualization
```

### 2. Add Your Project or Feature

If you want to add a new project, create a separate folder for it in the appropriate location within the repository.

Each new project should include:

- A clear project name and purpose.
- A `README.md` explaining the project, its features, and how to run it.
- The required source code and dependencies.
- Any necessary setup instructions.
- The contributor's name or GitHub username.

Before adding your work, make sure it follows the existing project structure and coding standards.

### 3. Commit Your Changes

Use clear, descriptive commit messages that explain what you changed.

**Commit message format:**

```text
<type>: <short description>
```

Recommended types:

- `feat`: Add a new feature or project.
- `fix`: Fix a bug.
- `docs`: Add or update documentation.
- `refactor`: Refactor existing code.
- `test`: Add or update tests.
- `chore`: Maintenance or configuration changes.

Examples:

```bash
git add .
git commit -m "feat: add radar visualization module"
```

```bash
git commit -m "docs: add setup instructions for radar project"
```

```bash
git commit -m "fix: resolve radar data processing issue"
```

### 4. Push Your Branch

Push your changes to your own branch, not directly to `main`.

```bash
git push -u origin feature/your-feature-name
```

For example:

```bash
git push -u origin feature/radar-visualization
```

### 5. Create a Pull Request (PR)

After pushing your changes:

1. Open the repository on GitHub.
2. Create a Pull Request from your branch into `main`.
3. Provide a clear title and description of your changes.
4. Explain what you added, why it is needed, and how it was tested.
5. Link any related issues, if applicable.

**Example PR title:**

`feat: add radar visualization module`

### 6. Team Leader Review and Approval

Every Pull Request must be reviewed by the team leader or an authorized reviewer before merging.

The reviewer may:

- Approve the changes.
- Request modifications.
- Leave comments or suggest improvements.
- Reject changes that do not meet project requirements.

If changes are requested, update your branch and push the new commits. The Pull Request will update automatically.

**Do not merge your own Pull Request unless the team leader has explicitly authorized it.**

### 7. Keep Your Branch Updated

Before starting new work, synchronize your local `main` branch:

```bash
git checkout main
git pull origin main
```

Then create a new branch for the next task. If your existing feature branch falls behind `main`, coordinate with the reviewer and update it as needed.

### Important Rules

- Never push directly to `main`.
- Every new project or feature must be developed on a separate branch.
- Every contribution must be submitted through a Pull Request.
- Wait for the required review and approval before merging.
- Write meaningful commit messages.
- Follow the existing folder structure and coding standards.
- Do not commit secrets, API keys, passwords, or environment files.
- Test your changes before submitting a Pull Request.
- Keep Pull Requests focused on one project, feature, or related task.

**Our goal is to collaborate, learn from one another, and maintain a clean, organized, and reliable codebase.**
