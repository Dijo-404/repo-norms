<a id="readme-top"></a>

<div align="center">

# repo-norms

**The coding standards, code quality rules, and templates I follow on every project.**

[![License](https://img.shields.io/github/license/Dijo-404/repo-norms?style=for-the-badge&color=555555)](LICENSE)
[![Markdown](https://img.shields.io/badge/Markdown-333333?style=for-the-badge&logo=markdown&logoColor=white)](#project-structure)
[![Last commit](https://img.shields.io/github/last-commit/Dijo-404/repo-norms?style=for-the-badge&color=555555)](https://github.com/Dijo-404/repo-norms/commits/main)

[Quick start](#quick-start) · [Usage](#usage) · [Documentation](#documentation) · [Contributing](#contributing)

</div>

<br/>

## Overview

repo-norms is a reference repository of the coding standards, code quality guidelines, and best practices I follow when building projects. Each norm is a plain Markdown file you can read on GitHub or copy straight into a new repository, so every project starts from the same baseline instead of being set up from memory.

### Features

- **Copy-ready templates.** Each file is meant to be dropped into a project and filled in, with placeholders written in CAPS.
- **Instructions built in.** Templates explain how to use them in HTML comments, which GitHub doesn't render.
- **One source of truth.** Standards live in one place, so updating a norm here updates the reference for every future project.

## Quick start

```bash
# Start a new project's README from the template
curl -fsSL https://raw.githubusercontent.com/Dijo-404/repo-norms/main/readme-norm.md -o README.md
```

Then replace every placeholder in CAPS, delete the sections marked `OPTIONAL` that don't apply, and remove the HTML comments.

## Usage

### Norms

| File | What it covers |
| :--- | :--- |
| [`readme-norm.md`](readme-norm.md) | README template. Sections follow the order a visitor asks questions in: what it is, why it matters, how to get it, how to use it, how it works, how to work on it, and whether they can use it. |

### Examples

**Use a norm in an existing project**

```bash
git clone https://github.com/Dijo-404/repo-norms.git
cp repo-norms/readme-norm.md path/to/project/README.md
```

## Project structure

```text
.
├── LICENSE          # MIT license
├── README.md        # this file
└── readme-norm.md   # README template
```

## Roadmap

- [x] README template
- [ ] Coding standards
- [ ] Code quality guidelines

## Documentation

| Guide | What's in it |
| :--- | :--- |
| [README template](readme-norm.md) | Section-by-section README structure with usage notes |

## Contributing

These are personal norms, but suggestions are welcome. Open an issue on [GitHub Issues](https://github.com/Dijo-404/repo-norms/issues) to propose a change or point out a gap.

## License

Released under the [MIT License](LICENSE).

<br/>

<div align="center">
  <sub>Built by <a href="https://github.com/Dijo-404">Dijo-404</a> · <a href="#readme-top">Back to top</a></sub>
</div>
