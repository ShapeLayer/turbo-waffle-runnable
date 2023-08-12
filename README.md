# turbo-waffle

Editorial Builder for the editorial of "2023 PIMM Algorithm Party"

**Notice**

This is a code written in a hurry in a short time. I cannot guarantee that it will always work in all environments. (Test Execution Environment: Github Codespaces with default configurations)

## Install dependencies

```sh
npm install
npm link
```

## Run

Enter the command below in a repository that has a folder and file structure supported by Turbo Waffle.

Detailed folder structure specifications will be updated later.

```sh
tw
tw --output=filename.pdf
```

## Why this repository's name is "turbo-waffle"?

That's Github's suggestion.

## Troubleshooting

**Could not find Chrome**

```
Error: Could not find Chrome (ver. **). This can occur if either
 1. you did not perform an installation before running the script (e.g. `npm install`) or
 2. your cache path is incorrectly configured (which is: **).
```

```sh
node node_modules/puppeteer/install.js
```
