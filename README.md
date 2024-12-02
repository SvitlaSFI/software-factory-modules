# 🗂️ Software Factory Modules

Welcome to the Software Factory Modules repository! This project is a collection of multiple coding examples and mini-projects aimed at providing reference and inspiration for developers.

## 📑 Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Git Workflow](#git-workflow)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## <a name="getting-started"></a>🚀 Getting Started

To get a local copy of the project up and running, follow these simple steps:

### Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/) 🐙
- [Docker](https://www.docker.com/) 🐋
- [Docker Compose](https://docs.docker.com/compose/) 🛠️

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lumina-svitla/svitla-design-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd svitla-design-system
   ```
3. Navigate to the mini-project that you want to try and follow the mini-project readme instructions:

## <a name="project-structure"></a>🏗️ Project Structure

The project is organized as follows:

```bash
svitla-design-system/
├── backend/
│ ├── python/
│ ├── nodejs-ts/
│ │ ├── basic-login/
│ │ ├── user-roles/
│ │ ├── ...
│ ├── ...
├── frontend/
│ ├── react/
│ ├── vue/
│ │ ├── login/
│ │ ├── internationalization/
│ │ ├── ...
│ ├── ...
├── .gitignore
├── README.md
├── CODE_OF_CONDUCT.md
├── CHANGELOG
├── LICENSE
└── ...
```

- **backend/**: Contains individual backend technologies that contains code examples and mini-projects developed in the respective technology.
- **frontend/**: Contains individual backend technologies that contains code examples and mini-projects developed in the respective technology (coming soon).
- **.gitignore**: Specifies files to ignore in the repository.
- **README.md**: The main README file.
- **LICENSE**: Contains the license information for the project.
- **CHANGELOG.md**: Contains a log of all changes made to the project.
- **CODE_OF_CONDUCT**: Contains the code of conduct for contribution based in the conduct-covenant code.

## <a name="git-workflow"></a>📚 Git Workflow

We follow a structured Gitflow to manage our development process. Here's a summary:

### Branches

- **main**: Contains the stable and production-ready code.
- **dev**: Integrates all features and is used for testing before merging into `main`.
- **feature/<feature-name>**: Used for developing new features or examples.
- **bugfix/<description>**: Used for fixing bugs.
- **hotfix/<description>**: Used for urgent fixes in production.
- **docs/<description>**: Used for updating documentation.

### Commands

1. **Creating a new feature branch**:

   ```bash
   git switch dev
   git pull origin dev
   git switch -C feature/<feature-name>
   ```

2. **Creating a bugfix branch**:

   ```bash
   git switch dev
   git pull origin dev
   git switch -C bugfix/<description>
   ```

3. **Creating a hotfix branch**:

   ```bash
   git switch main
   git pull origin main
   git switch -C hotfix/<description>
   ```

4. **Creating a documentation branch**:
   ```bash
   git switch main
   git pull origin main
   git switch -C docs/<description>
   ```

## <a name="contributing"></a>🤝 Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git switch -C feature/feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/feature-name`).
6. Open a Pull Request.

Please make sure to update tests as appropriate and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## <a name="license"></a>📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## <a name="contact"></a>📬 Contact

- **Project Maintainer**: [Fausto Emanuel Perez](https://github.com/lumina-svitla)
- **Email**: e.perez@svitla.com