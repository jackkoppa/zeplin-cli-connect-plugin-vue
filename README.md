# Zeplin CLI Connected Components - Vue Plugin

[![npm version](https://badge.fury.io/js/zeplin-cli-connect-plugin-vue.svg)](https://badge.fury.io/js/zeplin-cli-connect-plugin-vue)

![Example Zeplin snippet created by the plugin](docs/example_snippet.png)

Zeplin CLI plugin, to send Vue component snippets to Zeplin

To use:

1. Follow instructions for setting up Zeplin Connected Components, and the required `components.json` file; see [Zeplin's blog post](https://blog.zeplin.io/introducing-connected-components-components-in-design-and-code-in-harmony-aa894ed5bd95) and the [`@zeplin/cli` package](https://www.npmjs.com/package/@zeplin/cli) (still in beta as of Dec. 2019)
2. Once your `components.json` is ready, then:
```bash
npm i @zeplin/cli -D
npm i zeplin-cli-connect-plugin-vue -D

npx zeplin connect -p zeplin-cli-connect-plugin-vue
```

And that's it! In addition to any Component or Storybook links you've setup, snippets for your `.vue` components will now be available alongside your Zeplin components

Please open issues with any additional information you'd like to see in your generated Zeplin snippets
