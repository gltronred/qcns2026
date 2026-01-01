# QCNS 2026 website

[![Deploy to GH Pages and Server](https://github.com/gltronred/qcns2026/actions/workflows/deploy.yml/badge.svg)](https://github.com/gltronred/qcns2026/actions/workflows/deploy.yml)

Compilation:

```sh
pnpm install
pnpm build
```

The resulting static files will be located in the `dist/` directory.

## TODO (technical)

- use a JSON file to populate important dates on the index, "CFP", and "Important dates" pages
- use a JSON file for schedule
- if there are invited speakers, add their information to the speakers page from a JSON

## TODO (content)

- add information about conference venue
- add beautiful picture to the index page

## TODO (organisational)

- confirm important dates
- add contact information (at least, email)
- provide link to EDAS on the CFP and submission pages
- add TPC members

## 🚀 Project Structure

Inside of the project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src
│   ├── assets
│   │   └── astro.svg
│   ├── components
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

The most important files are `src/components/NavBar.astro`, which contains the navigation bar, and `src/pages/`, where all the pages are located.

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
