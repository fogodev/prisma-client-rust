<div align="center">
    <h1>Prisma Client Rust</h1>
    <p><b>Type-safe database access for Rust</b></p>
    <img src="https://img.shields.io/badge/latest-0.6.0-blue?style=flat-square" alt="Latest version of Prisma Client Rust is 0.6.0">
    <a href="https://prisma.io">
        <img src="https://img.shields.io/static/v1?label=prisma&message=v3.13.0&color=blue&logo=prisma&style=flat-square" alt="Latest supported Prisma version is 3.13.0">
    </a>
    <img src="https://img.shields.io/github/workflow/status/Brendonovich/prisma-client-rust/CI?label=tests&style=flat-square" alt="Test Status"/>
    <a href="https://github.com/Brendonovich/prisma-client-rust/blob/dev/docs/README.md"/>
    <img src="https://img.shields.io/badge/docs-latest-blue?style=flat-square" alt="Link to latest Documentation files">
    </a>
    <a href="https://github.com/Brendonovich/prisma-client-rust/discussions">
        <img src="https://img.shields.io/badge/chat-discussions-blue?style=flat-square&logo=github" alt="Prisma Client Rust uses GitHub Discussions as a place to chat and ask questions">
    </a>
</div>

<br>

Prisma Client Rust is an autogenerated query builder that provides simple and fully type-safe database access without macros or domain-specific languages. It is an alternative to ORMs like [Diesel](https://diesel.rs/) and [SeaORM](https://www.sea-ql.org/SeaORM/) and tools like [SQLx](https://github.com/launchbadge/sqlx).

## Why Prisma Client Rust?

For experienced Rust developers, Prisma Client Rust provides a much more consistent and understandable API than other ORMs, which typically hide a lot of code with macros - not that macros are bad, just that complex ones can be quite unwieldly to debug.

For developers looking to step away from NodeJS and create faster, more efficient applications, Prisma Client Rust harnesses existing tooling and terminology that Prisma Client JS users will be familiar with, making developing applications in Rust more approachable.

Also - perhaps for the first time - using Prisma in a frontend application is easy. Using Prisma Client Rust for a desktop application powered by [Tauri](https://tauri.studio/) allows the entire Prisma ecosystem to be used in developing desktop applications. (Though applying migrations to end users can be tricky - this will likely be improved)

## Getting Started

Read the [installation instructions](docs/01-installation.md) to get started and setup the CLI.

For more general information about Prisma and its CLI, check out the [official Prisma docs](https://www.prisma.io/docs/).

## Support

If you have any questions, feel free to ask in a [new discussion](https://github.com/RobertCraigie/prisma-client-py/discussions/new) or ping me in the [Prisma Slack](https://slack.prisma.io/) `@Brendan Allan`

## Versioning

Prisma Client Rust is not stable.

Breaking changes will be documented and released under a new MINOR version following this format.

`MAJOR`.`MINOR`.`PATCH`

There is no release schedule, as I work on this alone and can't guarantee updates.

## Affiliation

Prisma Client Rust is not an official Prisma product, only a community made layer on top of Prisma's engines.

## Acknowledgements

- [steebchen](https://github.com/steebchen) and all other contributors to [Prisma Client Go](https://github.com/prisma/prisma-client-go) for writing a lot of code and documentation that Prisma Client Rust basically copies. Without Prisma Client Go, this project would not have even been attempted.
- [seunlanlege](https://github.com/seunlanlege) for their work on [prisma-client-rs](https://github.com/polytope-labs/prisma-client-rs) which was used while integrating Prisma's query engine crates.
- [Prisma](https://prisma.io) for developing a brilliant and flexible open source ORM.
- [Robert Craige](https://github.com/sponsors/RobertCraigie) for writing tests for [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) that I have adapted.
