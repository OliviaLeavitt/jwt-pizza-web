# JWT Pizza Web

A React and TypeScript pizza-ordering client developed from the devops329 JWT Pizza
course project. This is a fork; upstream application code and its MIT license remain intact.

My coursework includes the GitHub Actions pipeline, browser/coverage testing,
load-testing exercises, and operational reports. The repository retains the
original application and course documentation.

## Engineering focus

- React views for diners and franchise/store administration.
- Playwright browser tests and coverage tooling.
- GitHub Actions build artifacts and coverage reporting.
- Load-test and incident-report exercises.
- AWS S3/CloudFront deployment configuration retained for reference.

## Run locally

```sh
npm ci
npm run dev
```

Run `npm run build` to generate `dist/`. Backend features require a configured
JWT Pizza service; see the environment files and
[original setup documentation](docs/original-readme.md).

Paired service: [JWT Pizza API](https://github.com/OliviaLeavitt/jwt-pizza-api).

The inherited CI workflow contains an AWS deployment job. Cleanup documentation
commits skip CI; no AWS deployment was requested or performed.
