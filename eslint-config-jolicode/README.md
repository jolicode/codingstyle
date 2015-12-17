# eslint-config-jolicode

This is [JoliCode](http://jolicode.com/)'s [ESLint](http://eslint.org/) configuration including EcmaScript 6+ and React.

By adopting this config, we encourage consistent style and quality across all of our repos.

We [extend](http://eslint.org/docs/user-guide/configuring.html#extending-configuration-files) [airbnb/javascript](https://github.com/airbnb/javascript) rules.

## Usage

```sh
npm install --save-dev eslint eslint-config-jolicode eslint-config-airbnb eslint-plugin-react babel-eslint
```

Create an `.eslintrc` file:
```json
{
  "extends": "jolicode"
}
```
