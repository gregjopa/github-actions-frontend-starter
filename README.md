# GitHub Actions Frontend Starter

[![build status][build-badge]][build]
[![code coverage][coverage-badge]][coverage]
[![apache license][license-badge]][license]

[build-badge]: https://img.shields.io/github/workflow/status/gregjopa/github-actions-frontend-starter/build?logo=github&style=flat-square
[build]: https://github.com/gregjopa/github-actions-frontend-starter/actions?query=workflow%3Abuild
[coverage-badge]: https://img.shields.io/codecov/c/github/gregjopa/github-actions-frontend-starter.svg?style=flat-square
[coverage]: https://codecov.io/github/gregjopa/github-actions-frontend-starter/
[license-badge]: https://img.shields.io/github/license/gregjopa/github-actions-frontend-starter.svg?style=flat-square
[license]: https://github.com/gregjopa/github-actions-frontend-starter/blob/main/LICENSE

This project includes some helpful GitHub Actions for frontend apps.

## Validating PRs

The `main.yml` workflow runs on every Pull Request and Push to the main branch. It's designed to lint, test, and build your app. It's also set up to use [codecov.io](https://codecov.io) for reporting code coverage.

## Managing PRs and Issues

The `stale.yml` workflow runs once a day and labels any PRs and Issues older than 90 days to see if they should be closed or not.

The `lock.yml` workflow runs once a day and locks old issues that have been closed for a year.

## Additional Info

- These workflows are heavily inspired by the ones used in [kcd-scripts](https://github.com/kentcdodds/kcd-scripts)
- https://github.com/actions/stale
- https://github.com/dessant/lock-threads
- https://github.com/sdras/awesome-actions
