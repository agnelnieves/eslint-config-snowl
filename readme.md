# Snowl Eslint & Prettier Setup

Plain and simple code quality config

* Lint JavaScript based on latest standards
* Fix issues and formatting errors
* Lint & Fix issues within html `<script>` tags

## ✨Quick Start

1. If you don't already have a `package.json` file, create one with `npm init`.

2. Install everything needed by the config:

```bash
npx install-peerdeps --dev eslint-config-snowl
```

## ⚙️ Setting up

1. Your package.json should have all the dependencies needed to run the script
2. Create a `.eslintrc` file in the root of your project. Your `.eslintrc` file should look like this:

```json
{
  "extends": [
    "snowl"
  ]
}
```

## 🏃🏻‍♂️Runnning the script

Add two scripts to your package.json to lint and/or fix:

```json
"scripts": {
  "lint": "eslint .",
  "lint:fix": "eslint . --fix"
},
```

### 🙌🏻 Happy coding!