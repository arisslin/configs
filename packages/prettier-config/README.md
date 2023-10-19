# @arissling/prettier-config

This is a prettier config for reuse.

## Install

First run the command bellow on your local repository.
```
npm i --save-dev @arissling/prettier-config
```

Then create a `prettierrc.json` file in the root folder of your repository.

```
touch .prettierrc.json
```

Add following line to `prettierrc.json`.
```
"@arissling/prettier-config"
```

## Settings

Below you can see the prettier configuration.

```
module.exports = {
  singleQuote: true,
  jsxSingleQuote: true,
  trailingComma: "es5",
};
```