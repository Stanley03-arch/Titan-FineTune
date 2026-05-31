# Contributing to Titan-FineTune

We welcome contributions to the Titan-FineTune project! To ensure a smooth and collaborative development process, please follow these guidelines.

## How to Contribute

1.  **Fork the Repository**: Start by forking the `Titan-FineTune` repository to your GitHub account.
2.  **Clone Your Fork**: Clone your forked repository to your local machine:

    ```bash
    git clone https://github.com/YOUR_USERNAME/Titan-FineTune.git
    cd Titan-FineTune
    ```

3.  **Create a New Branch**: Create a new branch for your feature or bug fix. Use a descriptive name (e.g., `feature/add-lora-support`, `bugfix/fix-dataloader-issue`).

    ```bash
    git checkout -b feature/your-feature-name
    ```

4.  **Make Your Changes**: Implement your changes, ensuring they adhere to the project's coding standards and best practices.

5.  **Test Your Changes**: Run existing tests and add new ones if necessary to cover your changes. Ensure all tests pass.

    ```bash
    # Example: Run unit tests
    pytest
    ```

6.  **Commit Your Changes**: Write clear and concise commit messages. Follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

    ```bash
    git commit -m "feat: Add new feature for X"
    ```

7.  **Push to Your Fork**: Push your local branch to your forked repository on GitHub.

    ```bash
    git push origin feature/your-feature-name
    ```

8.  **Create a Pull Request (PR)**: Open a pull request from your forked repository to the `main` branch of the original `Titan-FineTune` repository. Provide a detailed description of your changes, including:

    *   What problem does this PR solve?
    *   How were the changes implemented?
    *   Any relevant test results or screenshots.

## Code Style

*   Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) for Python code.
*   Use type hints for all function signatures.
*   Document your code with clear docstrings.

## Reporting Bugs

If you find a bug, please open an issue on the GitHub issue tracker. Provide as much detail as possible, including:

*   A clear and concise description of the bug.
*   Steps to reproduce the behavior.
*   Expected behavior.
*   Screenshots or error messages if applicable.
*   Your environment details (OS, Python version, installed packages).

## Suggesting Enhancements

We welcome suggestions for new features or improvements. Please open an issue on the GitHub issue tracker to discuss your ideas.

## Code of Conduct

By contributing to Titan-FineTune, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

Thank you for contributing to Titan-FineTune!
