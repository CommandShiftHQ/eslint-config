# eslint-config-mcr-codes
 
eslint config for learning to code

## Install
Install the npm package as a dev dependency
`npm install eslint-config-mcr-codes --save-dev`

## Setup
Add an `.eslintrc` file at the root of your project with the following content:

```json
{
  "extends": [
    "mcr-codes"
  ]
}
```

If your project is a React project, add `"mcr-codes/react"` instead of just `"mcr-codes"`

