<div align="center">

<img src="https://raw.githubusercontent.com/esliph/.github/refs/heads/master/assets/logos/esliph-logo-negative.svg" height="120">

**Technologies and packages for application development.**

</div>

---

Esliph builds its own application infrastructure - dependency injection, metadata, validation, data structures and neural networks - instead of adopting off-the-shelf libraries. The goal is to understand and control every piece of the toolchain, with declarative APIs, minimal dependencies and the same engineering rigor at any scale.

## Packages

### Foundation

| Repository                                       | Description                                                                                                                                                  |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [metadata](https://github.com/esliph/metadata)   | Metadata for classes, methods, properties and parameters, with isolated containers. A dependency-free replacement for `reflect-metadata`.                     |
| [injection](https://github.com/esliph/injection) | Dependency injection container with TC39 stage 3 decorators, singleton and request scopes, `useValue`, `useFactory`, `useClass` and circular dependency support. |

### Validation

| Repository                                                         | Description                                                                                                                        |
| ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| [liph-validator-php](https://github.com/esliph/liph-validator-php) | Zod-inspired schema validation for PHP 8.2+: primitive types, objects, unions, coercion and `ParseResult`. Zero runtime dependencies. |

### Fundamentals

| Repository                                         | Description                                                                                                       |
| -------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [Bitstalk](https://github.com/esliph/Bitstalk)     | Data structures in TypeScript - linked lists, stacks, queues, deques and heaps - in both array and linked versions. |
| [NeuroForge](https://github.com/esliph/NeuroForge) | Dense neural network in C++17 written from scratch, using only the STL, trained by a genetic algorithm.            |

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
