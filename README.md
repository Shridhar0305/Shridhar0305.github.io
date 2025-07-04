# My academic webpage

Remember to change permissions of GITHUB_TOKEN; see [here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#setting-the-permissions-of-the-github_token-for-your-repository).

## Instructions to setup and run locally

- Follow the instructions [here](https://github.com/imfing/vuepress-homepage?tab=readme-ov-file#------getting-started--) to install required tools (Node.js and yarn).
- Run `corepack enable` to add `yarn` binary to PATH
- Run `yarn global add vuepress`
- Run `export NODE_OPTIONS=--openssl-legacy-provider` to fix an error after running `yarn dev`
- Run `yarn` followed by `yarn dev`

May prefer to build static site locally (observed different behaviour to development mode above); this can be done as follows:
```
yarn clean
yarn build
http-server dist/
```
`http-server` needs to be installed using `npm`.

## Acknowledgements

- [imfing/vuepress-homepage](https://github.com/imfing/vuepress-homepage/tree/master) for the base website design
- [denis-ev/denis-ev.github.io](https://github.com/denis-ev/denis-ev.github.io) for the Github actions page deployment
- [https://dvtailor.github.io/](https://github.com/dvtailor/dvtailor.github.io) for the adaptation template of code and the website.