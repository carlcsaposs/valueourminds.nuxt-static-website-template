TODO: Add redirects in "static/\_redirects"

TODO: If the website should appear on search engines, remove the noindex header in "static/\_headers"

TODO: Change repository name in if-statement in `.github/workflows/deploy-dev.yml` and `.github/workflows/deploy-prod.yml`

TODO: Update copyright year in LICENSE, if neccessary

TODO: Configure repository settings

- Only allow squash merge
- Enable automatic deletion of head branches
- Add branch protection to "main"
  - Require status checks
    - Require branches be up to date
    - Require the 'deploy-dev' status check
    - Require linear history
    - Include administrators
- Add Dependabot security alerts for valueourminds/everyone
- Add write access for valueourminds/everyone
- Disable releases & packages from displaying on the home page
- Add "dependencies" label with color #d4c5f9
- Enable "NETLIFY_AUTH_TOKEN" organization secret for repository
- Add "NETLIFY_SITE_ID" repository secret

TODO: Add site in Netlify & disable form detection

TODO: Remove TODO comments from this README file

# Build Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/395e08a2-11e0-4b19-93a2-59a25a86fffa/deploy-status)](https://app.netlify.com/sites/vom-nuxt-static-website-template/deploys)

TODO: Replace Netlify deploy status badge (above in this README file)

# Contributing

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
