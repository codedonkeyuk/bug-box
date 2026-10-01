# Bug Box

This site was an epic disaster which is why it can only be found in cursed section of my website. I wanted it to be scary but its really sad. Anyway its done now!

Vite has been configured to generate icons off a single svg file. This svg file is also used for social media image. You need to edit [./public/logo-square.svg](./public/logo-square.svg) to change all the images used in the app for social sharing and icons.

## instructions

| code                | description                                                                |
| ------------------- | -------------------------------------------------------------------------- |
| `npm install`       | install dependencies                                                       |
| `nvm use`           | Use node version specified in projects .nvmrc file. (NVM needs installing) |
| `nvm run test`      | run jest tests                                                             |
| `nvm run serveDev`  | serve site in development mode (vite), unzipped with livereload (vite)     |
| `nvm run serveProd` | serve site in production mode (vite), zipped no reload                     |
| `nvm run clean`     | clean project with prettier                                                |
| `nvm run validate`  | validate code with typescript & prettier compiler                          |
| `nvm run build`     | Build site, validates files before doing so                                |

## General Instructions

### Update libraries

How to update libraries to the latest

```bash
npx npm-check-updates -u
npm install
```

### Update node

This project has been set up to use a specific version of node via `.nvmrc` file. Run this command to update to you local version.

```bash
nvm ls-remote --lts # see latest build
nvm install node # update to the latest build
node -v > .nvmrc # this project to the latest
```
