# Contributing

Want to contribute? Great! First, read this page.

## Linting and testing

We use PHP Coding Standards Fixer to maintain coding standards and PHPUnit to run our tests. For convenience, there are Composer scripts to run each of these:

```sh
composer run-script lint
composer run-script lint-fix
composer run-script test
```

These are run automatically by [GitHub Actions](https://github.com/phpfui/recaptcha/actions) against your Pull Request, but it's a good idea to run them locally before submission to avoid getting things bounced back. That said, tests can be a little daunting so feel free to submit your PR and ask for help.

## Code reviews

All submissions, including submissions by project members, require review. Reviews are conducted on the Pull Requests. The reviews are there to ensure and improve code quality, so treat them like a discussion and opportunity to learn. Don't get disheartened if your Pull Request isn't just automatically approved.
