# estlint-config-styleguide-recommended

Sain default coding style  
Can be applied in any language  

## Rules

* require or disallow newline at the end of files (`"eol-last": ["error", "always"]`})
* enforce consistent indentation (`"indent": ["error", 2]`)
* enforce consistent linebreak style (`"linebreak-style": ["error", "unix"]`)
* enforce a maximum line length (`"max-len": ["error", 80]`)
* disallow trailing whitespace at the end of lines (`"no-trailing-spaces": "error"`)

## Installation

```sh
npm install --save-dev estlint-config-styleguide-recommended
``` 
`.eslintrc`
```eslint
{
    "extends": "styleguide-recommended"
}
```

## Todo
* [ ] Test eslint rules