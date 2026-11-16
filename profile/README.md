<div align="center">

<img src="https://raw.githubusercontent.com/esliph/.github/refs/heads/master/assets/logos/esliph-logo-negative.svg" height="120">

**Technologies and packages for application development.**

</div>

---

Esliph builds its own application infrastructure - dependency injection, metadata, validation, data structures and neural networks - instead of adopting off-the-shelf libraries. The goal is to understand and control every piece of the toolchain, with declarative APIs, minimal dependencies and the same engineering rigor at any scale.

## Principles

**Build before depending.**
Zero runtime dependencies whenever possible. Reimplementing is a way to fully understand the tool.

**Wrap when it pays off.**
Established libraries are not rewritten without reason - when reimplementing brings no gain, the answer is to wrap them.

**Rigor over reach.**
Tests, atomic commits, Conventional Commits, exceptions with error codes and documentation are part of the work, not an afterthought.

**Reproducible environment.**
Docker, Makefile and GitHub Actions standardize development, testing and publishing across every project.

## Stack

| Area                | Tools                       |
| ------------------- | --------------------------- |
| Languages           | TypeScript, PHP 8.2+, C++17 |
| Testing             | Vitest, PHPUnit, doctest    |
| Build & environment | Docker, Makefile, CMake     |
| CI/CD               | GitHub Actions              |

---

<div align="center">

<sub>Maintained by <a href="https://github.com/Danrley-Ruan-Saquetti">Danrley-Ruan-Saquetti</a></sub>

</div>
