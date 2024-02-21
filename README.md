# Amplify Package Manager Demo

This is a demo of Amplify support for various package managers. See the PRs tab to see PRs for each package manager

## Npm

The `main` branch and `npm` branch of this repo use npm package manager. The `npm` branch is set up with an `amplify.yml` that works for PR previews.

```bash
git clone --single-branch --branch npm amplify-package-managers amplify-package-managers-npm
cd amplify-package-managers-npm
npm ci
npm run sandbox # kill this after deployment completes
npm run build
```

Currently, npm support is working well both locally as well as in Amplify Hosting CI/CD environment.

## Yarn 1.x