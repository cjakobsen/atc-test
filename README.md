### General Project Info
[![Github top language](https://img.shields.io/github/languages/top/atc-net/atc-test)](https://github.com/atc-net/atc-test)
[![Github stars](https://img.shields.io/github/stars/atc-net/atc-test)](https://github.com/atc-net/atc-test)
[![Github forks](https://img.shields.io/github/forks/atc-net/atc-test)](https://github.com/atc-net/atc-test)
[![Github size](https://img.shields.io/github/repo-size/atc-net/atc-test)](https://github.com/atc-net/atc-test)
[![Issues Open](https://img.shields.io/github/issues/atc-net/atc-test.svg?logo=github)](https://github.com/atc-net/atc-test/issues)

### Packages
[![Github Version](https://img.shields.io/static/v1?logo=github&color=blue&label=github&message=latest)](https://github.com/orgs/atc-net/packages?repo_name=atc-test)
[![NuGet Version](https://img.shields.io/nuget/v/Atc.Test.svg?logo=nuget)](https://www.nuget.org/profiles/atc-net)

### Build Status
![Pre-Integration](https://github.com/atc-net/atc-test/workflows/Pre-Integration/badge.svg)
![Post-Integration](https://github.com/atc-net/atc-test/workflows/Post-Integration/badge.svg)
![Release](https://github.com/atc-net/atc-test/workflows/Release/badge.svg)

### Code Quality
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=atc-test&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=atc-test)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=atc-test&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=atc-test)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=atc-test&metric=security_rating)](https://sonarcloud.io/dashboard?id=atc-test)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=atc-test&metric=bugs)](https://sonarcloud.io/dashboard?id=atc-test)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=atc-test&metric=vulnerabilities)](https://sonarcloud.io/dashboard?id=atc-test)

# ATC Test

Common tools for writing tests using XUnit, AutoFixture, NSubstitute and FluentAssertions.

## Attributes

| Name | Description |
|-|-|
| `AutoNSubstituteData` | Provides auto-generated data specimens generated by AutoFixture and NSubstitute as an extension to XUnit's [Theory] attribute.|
| `InlineAutoNSubstituteData` | Provides a data source for a data theory, with the data coming from inline values combined with auto-generated data specimens generated by AutoFixture and NSubstitute.|
| `MemberAutoNSubstituteData` | Provides a data source for a data theory, with the data coming from one of the following sources and combined with auto-generated data specimens generated by AutoFixture and NSubstitute.|


Note: NSubstitute is used when the type being created is abstract, or when the `[Substitute]` is applied.

# The workflow setup for this repository
[Read more on Git-Flow](docs/GitFlow.md)

# Contributing

Please refer to each project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow. [Read more here](https://gist.github.com/Chaser324/ce0505fbed06b947d962).

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull request** so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

# Coding Guidelines

This repository is adapting the [ATC-Coding-Rules](https://github.com/atc-net/atc-coding-rules) which is defined and based on .editorconfig's and a range of Roslyn Analyzers.
