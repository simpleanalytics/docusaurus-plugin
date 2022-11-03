# Simple Analytics Docusaurus Plugin

[Simple Analytics](https://simpleanalytics.com/) plugin for Docusaurus.

## Setup

Install the package `docusaurus-plugin-simple-analytics`:

```
npm install --save docusaurus-plugin-simple-analytics
```

Or

```
yarn add docusaurus-plugin-simple-analytics
```

Then, add the plugin to `docusaurus.config.js`:

```
plugins: [
  ...
  ['docusaurus-plugin-simple-analytics', {}],
  ...
],
```

## Options

- The property `domain` lets you specify [your custom domain](https://docs.simpleanalytics.com/bypass-ad-blockers).

**Example**

```
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

Developed by https://www.branchup.tech (https://github.com/branchup).

## License

Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php)
