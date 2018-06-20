# eslint-config-mcr-codes
 
eslint config for learning to code

## Install
Install the npm package as a dev dependency
`npm install eslint-config-mcr-codes --save-dev`

Then install the peer-dependencies
`npm install eslint eslint-plugin-import eslint-plugin-react --save-dev`

## Setup
In your `.eslintrc` file add the following:

```json
{
  ...
  "extends": [
    "mcr-codes"
  ]
}
```

If your project is a React project, add `"mcr-codes/react"` instead of just `"mcr-codes"`

