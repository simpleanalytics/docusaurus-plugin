# Simple Analytics Docusaurus Plugin

[Simple Analytics](https://www.simpleanalytics.com/) plugin for Docusaurus. [See the documentation](https://docs.simpleanalytics.com/install-simple-analytics-with-docusaurus) at Simple Analytics.

## Setup

Install the package `docusaurus-plugin-simple-analytics`:

```
npm install docusaurus-plugin-simple-analytics@1.1.5 --save
```

Or

```
yarn add docusaurus-plugin-simple-analytics@1.1.5
```

Then, add the plugin to `docusaurus.config.js`:

```js
plugins: [
  ...
  ['docusaurus-plugin-simple-analytics', {}],
  ...
],
```

## Custom domain

The property `domain` lets you specify [your custom domain](https://docs.simpleanalytics.com/bypass-ad-blockers).

Example:

```js
plugins: [
  ...
  ['docusaurus-plugin-simple-analytics', {
    domain: 'custom.domain.com'
  }],
  ...
],
```

## Notes

The plugin has no effect in development.

## Special thanks

Developed by [Frédéric Massart](https://github.com/FMCorz) from [branchup.tech](https://www.branchup.tech/?utm_source=github.com%2Fsimpleanalytics%2Fdocusaurus-plugin) ([@branchup](https://github.com/branchup)). 

## License

Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php)
