<p align="center"><img src="https://raw.githubusercontent.com/titaniumnetwork-dev/Ultraviolet-Static/main/public/uv.png" height="200"></p>

<h1 align="center">Ultraviolet-App-Gitpod</h1>

The deployable all-in-one bundle for Ultraviolet, a highly sophisticated proxy used for evading internet censorship or accessing websites in a controlled sandbox using the power of service-workers and more!

[![Codespaces Prebuilds](https://github.com/catfoolyou/Ultraviolet-App/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/catfoolyou/Ultraviolet-App/actions/workflows/codespaces/create_codespaces_prebuilds)
[![ESLint](https://github.com/catfoolyou/Ultraviolet-App/actions/workflows/eslint.yml/badge.svg)](https://github.com/catfoolyou/Ultraviolet-App/actions/workflows/eslint.yml)

<a target="_blank" href="https://gitpod.io/#https://github.com/catfoolyou/Ultraviolet-App">
        <img src="https://img.shields.io/badge/Deploy_with-Gitpod-orange" alt="UV Gitpod Development Environment" />
    </a>

## Deployment

None of the web deployment services listed on the TN page are currently available.
Currently, the only feasible way to deploy this service is using gitpod, see below.

### Deploying with Gitpod
1. Go to [gitpod.io/#https://github.com/catfoolyou/Ultraviolet-App](gitpod.io/#https://github.com/catfoolyou/Ultraviolet-App)
2. Hit open workspace and wait for it to deploy, this might take a while on crappy wifi.
3. When the dialog pops up in the lower right corner, hit "make public". DO NOT open in browser, this will redirect you to a broken web link.
4. Navigate to "Ports", make sure "State" is set to public[^1], and click the link under "Address".

   [^1]: If it isnt, click the lock icon.

### FAQ
1. Gitpod has a timeout for free deployments (around 2 hours I think), so just check back on the page from time to time.
2. If you get a dialog about service workers, just click "register service worker".
3. If you get a window saying that the environment does not exist, deploy again. This is because Gitpod sometimes moves free web apps from one server to the other.
