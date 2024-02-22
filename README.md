## Idea-Orbit

is a web app that helps aspiring students to capture and organize their business ideas. Users can sign up, create their Idea Book, and jot down their concepts in a structured way. It features an easy-to-use interface, customizable templates, and tools for collaboration, aiming to turn inspiration into actionable plans. Perfect for anyone starting their entrepreneurial journey!.

## Website Link

https://ideaorbit.vercel.app/

<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
</p>
<p align="center">
    <h1 align="center">IDEA-ORBIT-</h1>
</p>
<p align="center">
    <em><code>► A website to note your ideas with OpenAI integration</code></em>
</p>

<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Firebase-FFCA28.svg?style=flat&logo=Firebase&logoColor=black" alt="Firebase">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style=flat&logo=PostCSS&logoColor=white" alt="PostCSS">
	<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style=flat&logo=Autoprefixer&logoColor=white" alt="Autoprefixer">
	<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
	<br>
	<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
	<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style=flat&logo=ESLint&logoColor=white" alt="ESLint">
	<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style=flat&logo=TypeScript&logoColor=white" alt="TypeScript">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>
<hr>

## Quick Links

> - [ Overview](#-overview)
> - [ Repository Structure](#-repository-structure)

> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [Running Idea-Orbit-](#-running-Idea-Orbit-)
>   - [ Tests](#-tests)

> - [ Contributing](#-contributing)

---

## Overview

<code>► Idea Orbitis a web app that helps aspiring students to capture and organize their business ideas. Users can sign up, create their Idea Book, and jot down their concepts in a structured way. It features an easy-to-use interface, customizable templates, and tools for collaboration, aiming to turn inspiration into actionable plans. Perfect for anyone starting their entrepreneurial journey.</code>

---

## Repository Structure

```sh
└── Idea-Orbit-/
    ├── README.md
    ├── components.json
    ├── drizzle.config.ts
    ├── next.config.mjs
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── public
    │   ├── next.svg
    │   └── vercel.svg
    ├── readme-ai.md
    ├── src
    │   ├── app
    │   │   ├── api
    │   │   │   ├── completion
    │   │   │   │   └── route.tsx
    │   │   │   ├── createIdeaBook
    │   │   │   │   └── route.ts
    │   │   │   ├── deleteIdea
    │   │   │   │   └── route.ts
    │   │   │   ├── savedIdea
    │   │   │   │   └── route.tsx
    │   │   │   └── uploadToFirebase
    │   │   │       └── route.tsx
    │   │   ├── dashboard
    │   │   │   └── page.tsx
    │   │   ├── favicon.ico
    │   │   ├── globals.css
    │   │   ├── ideabook
    │   │   │   └── [ideaId]
    │   │   │       └── page.tsx
    │   │   ├── layout.tsx
    │   │   ├── page.tsx
    │   │   ├── sign-in
    │   │   │   └── [[...sign-in]]
    │   │   │       └── page.tsx
    │   │   └── sign-up
    │   │       └── [[...sign-up]]
    │   │           └── page.tsx
    │   ├── components
    │   │   ├── CreateIdeaDialog.tsx
    │   │   ├── DeleteButton.tsx
    │   │   ├── Editor.tsx
    │   │   ├── EditorMenuBar.tsx
    │   │   ├── Provider.tsx
    │   │   └── ui
    │   │       ├── TypewriterTitle.tsx
    │   │       ├── button.tsx
    │   │       ├── dialog.tsx
    │   │       ├── input.tsx
    │   │       └── separator.tsx
    │   ├── done.ts
    │   ├── lib
    │   │   ├── clerk.server.ts
    │   │   ├── db
    │   │   │   ├── index.ts
    │   │   │   └── schema.ts
    │   │   ├── firebase.ts
    │   │   ├── openai.ts
    │   │   ├── useDebounce.ts
    │   │   └── utils.ts
    │   └── middleware.ts
    ├── tailwind.config.ts
    └── tsconfig.json
```

---

## Getting Started

### Installation

1. Clone the Idea-Orbit- repository:

```sh
git clone https://github.com/Khushisidanaa/Idea-Orbit-.git
```

2. Change to the project directory:

```sh
cd Idea-Orbit-
```

3. Install the dependencies:

```sh
npm install
```

### Running `Idea-Orbit-`

Use the following command to run Idea-Orbit-:

```sh
npm run build && node dist/main.js
```

### Tests

Use the following command to run tests:

```sh
npm test
```

## Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Khushisidanaa/Idea-Orbit-.git/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Khushisidanaa/Idea-Orbit-.git/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Khushisidanaa/Idea-Orbit-.git/issues)**: Submit bugs found or log feature requests for the `Idea-Orbit-` project.

<details closed>
    <summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/Khushisidanaa/Idea-Orbit-.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

</details>

---
