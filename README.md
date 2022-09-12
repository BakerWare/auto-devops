# Auto-devops

Holds all shared workflows.

### Publish composer package

- [composer-package.yml](https://github.com/BakerWare/auto-devops/blob/main/.github/workflows/composer-package.yml)

1. Builds the package 
2. Run test
3. Publish to [Repman](https://repman.bwnet.nl/organization/bakerware/package)
4. Notify slack

### Deploy Vue monorepo

- [deploy-windows-mono-vue.yml](https://github.com/BakerWare/auto-devops/blob/main/.github/workflows/deploy-windows-mono-vue.yml)

1. Build .env files
2. Build apps
3. Add workflow option to deploy app
4. Notify Slack

<<<<<< example image >>>>>>

### Deploy Vue app

- [deploy-windows-vue.yml](https://github.com/BakerWare/auto-devops/blob/main/.github/workflows/deploy-windows-vue.yml)

1. Build .env files
2. Build app
3. Add workflow option to deploy app
4. Notify Slack

### Definition of done

- [dod.yml](https://github.com/BakerWare/auto-devops/blob/main/.github/workflows/dod.yml)

1. Add checklist to pull requests

### Publish npm package

- [npm-package.yml](https://github.com/BakerWare/auto-devops/blob/main/.github/workflows/npm-package.yml)

1. Build package
2. Publish to [Github registry](https://github.com/orgs/BakerWare/packages)
3. Notify Slack
