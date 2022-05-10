# use-eslint-and-prettier

## install and init eslint on terminal


`npm install eslint --save-dev`

`npm init @eslint/config`

## install prettier and create configure file

`npm install --save-dev --save-exact prettier`

`echo {}> .prettierrc.json`


## let eslint and prettier work together without conflicts

`npm install --save-dev eslint-config-prettier`

add prettier to eslint extension on the config file.

`{
  "extends": [
    "some-other-config-you-use",
    "prettier"
  ]
}`
