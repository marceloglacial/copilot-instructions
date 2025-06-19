# GitHub Copilot Instructions

This repository provides comprehensive guidelines for using **GitHub Copilot** to generate high-quality, consistent, and performant code for **React and Next.js applications**.

## What You'll Find

The `copilot-instructions.md` file within this repository serves as the central resource, detailing best practices and conventions that Copilot should adhere to. It covers a wide range of topics, including:

* **General Principles:** Emphasizing clean code, conciseness, descriptive naming, DRY principles, modularization, and a **TypeScript-first** approach.
* **Project Structure:** Guidelines on colocation, the use of `lib/` for utilities, private folders, and the avoidance of barrel files.
* **React Specific Guidelines:** Detailed instructions on component design (functional components, hooks, single responsibility), state management (local and global), styling with Tailwind CSS, and performance optimizations.
* **Next.js Specific Guidelines:** Guidance on data fetching and rendering with the App Router, routing conventions, optimization techniques (images, fonts, dynamic imports), and SEO/accessibility considerations.
* **TypeScript Best Practices:** Ensuring strict mode, accurate type definitions, and organized type files within the `types/` folder.
* **Examples:** Concrete examples of how Copilot should respond to specific prompts, demonstrating the expected code style and structure.

---

## Getting Started

To understand the full scope of these guidelines and how they influence code generation, please refer to the `copilot-instructions.md` file. These instructions are designed to help developers maintain a unified and efficient codebase when working with GitHub Copilot on React and Next.js projects.

You can also find a related LinkedIn post discussing these instructions [here](https://www.linkedin.com/posts/glacial_ai-devtips-vscode-activity-7338937165243924480-1isM?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAJ84gEB0WHDx8HvexO4IDStSiLg7kCpT2s).

## How to Use with VS Code

To leverage these instructions with GitHub Copilot in VS Code, ensure you have the GitHub Copilot extension installed. You can find detailed information on customizing Copilot's behavior and integrating project-specific guidelines in the official VS Code documentation:

* [**GitHub Copilot Customization in VS Code**](https://code.visualstudio.com/docs/copilot/copilot-customization)

This resource will guide you on how Copilot processes context from your project files, including markdown files like `copilot-instructions.md`, to provide more relevant and aligned suggestions.
