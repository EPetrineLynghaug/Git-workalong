# Lecture Notes: Git, GitHub, and GitHub Actions

## Description
In these lectures, we dive deeper into project organization and version control systems using Git and GitHub. We focus on using the terminal for Git operations and explore the powerful automation capabilities of GitHub Actions. The demo is just a proof of concept.

## Key Features of Git and GitHub
<details>
  <summary><strong>Click to read more</strong></summary>

  - **Version Control:** Manage and track changes across a collaborative environment.
  - **Git CLI:** Provides more control and flexibility than GUI alternatives.
  - **Branches and Pull Requests:** Crucial for managing contributions and reviewing code.
  - **SSH Keys:** Securely authenticate and interact with repositories.
  - **GitHub Actions:** Automate workflows for deployment, testing, and more.

</details>

## Advantages of Using Git from the Terminal
<details>
  <summary><strong>Click to read more</strong></summary>

1. **Full Control:** Access to a broader range of Git commands and options not available in desktop interfaces.
2. **Efficiency:** Terminal commands are faster and more versatile, particularly when switching branches or committing changes.
3. **Flexibility:** The ability to work on machines without Git GUI installed.
4. **Better Documentation Support:** The CLI provides access to more comprehensive help and resources online.
5. **Automation:** Integration with scripts for automation.

</details>

## GitHub Actions Overview
<details>
  <summary><strong>Click to read more</strong></summary>

1. **Automate Jobs:** GitHub Actions can automate various tasks, such as deployments and code testing.
2. **Trigger on Events:** Set up actions that trigger on events like push, commit, or pull requests.
3. **Custom Workflows:** Use YAML configuration files to define complex workflows that can run on different environments.
4. **Reusable Components:** Define reusable actions to streamline processes like code linting or formatting.
5. **Support for Various Runners:** Choose environments (Windows, Linux, macOS) for your workflows.

</details>

## Commonly Used GitHub Actions
<details>
  <summary><strong>Click to read more</strong></summary>

1. **Checkout Action (`actions/checkout`):** Used to check out your repository code so the workflow can access it.
2. **Setup Node.js Action (`actions/setup-node`):** Sets up the Node.js environment for running JavaScript/TypeScript projects.
3. **Run Tests with Jest (`jest-action`):** Automatically runs tests in your project with Jest, a popular testing framework.
4. **Linting with ESLint (`github/super-linter`):** Automatically lints your codebase to ensure code quality and consistency.
5. **Deploy to GitHub Pages (`peaceiris/actions-gh-pages`):** Automates the deployment of static sites to GitHub Pages.
6. **Build and Push Docker Images (`docker/build-push-action`):** Builds and pushes Docker images to a container registry.
7. **Trigger CI Pipelines (`actions/trigger-pipeline`):** Useful for triggering external CI/CD systems such as Jenkins or GitLab CI.

</details>

## Workflow Configuration
<details>
  <summary><strong>Click to read more</strong></summary>

1. **Event-Driven:** Workflows trigger based on events (e.g., a push to a branch or a pull request).
2. **YAML Definition:** Workflow steps are defined in YAML files, housed in the `.github/workflows` directory.
3. **Steps and Jobs:** Jobs consist of multiple steps that are executed in order, and can have dependencies on each other.
4. **Environment Setup:** Workflows can be configured to run in specific environments, such as staging, testing, or production.
5. **Scheduling:** Workflows can be triggered on a schedule (e.g., nightly builds).

</details>

## In this project, we aim to:
<details>
  <summary><strong>Click to read more</strong></summary>


- **Build a multi-page application with various routes.**
- **Implement middleware to handle tasks like managing date information.**

</details>
