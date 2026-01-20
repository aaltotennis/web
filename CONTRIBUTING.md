# Contributing to Aalto Tennis Website

Thank you for your interest in contributing to the Aalto Tennis website! We welcome contributions from everyone, whether you are a developer or a club member looking to update content.

Please choose the section below that best describes your contribution type.

## 📝 For Content Contributors (Updating Information)

If you want to update text, dates, or general information on the website, you don't need to be a programmer! The website content is written in Markdown files located in the `src/` folder.

### Quick Edit via GitHub (Recommended)

The easiest way to make small changes is directly through the GitHub website:

1.  Navigate to the file you want to change in the `src/` folder.
    *   **Home Page**: [`src/index.md`](src/index.md)
    *   **Board Members**: [`src/board.md`](src/board.md)
    *   **Join/Membership**: [`src/join.md`](src/join.md)
2.  Click the pencil icon (✎) in the top right corner of the file view to edit.
3.  Make your text changes.
4.  Scroll to the bottom to "Commit changes".
5.  Select "Create a new branch for this commit and start a pull request".
6.  Click "Propose changes".

### What Files to Edit
*   Most content is text inside `.md` (Markdown) files.
*   You can edit text freely, but try to keep the structure (headers starting with `#`, links like `[text](url)`) intact.

---

## 💻 For Code Contributors (Developers)

If you are working on the layout, styling, or build process, follow these technical instructions.

### Prerequisites

This project uses **Bun** as a package manager and runtime.
- [Install Bun](https://bun.sh/docs/installation)

### Setup

1.  Clone the repository:
    ```bash
    git clone https://github.com/aaltotennis/web.git
    cd web
    ```

2.  Install dependencies:
    ```bash
    bun install
    ```

### Development

To start the local development server with live reload:

```bash
bun start
```

Open `http://localhost:8080` in your browser to see the site.

### Building

To build the project for production:

```bash
bun run build
```

### Pull Request Process

1.  Create a new branch for your feature or fix: `git checkout -b feature/my-new-feature`
2.  Commit your changes.
3.  Push to the branch: `git push origin feature/my-new-feature`
4.  Open a Pull Request on GitHub.
