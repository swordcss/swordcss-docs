---
id: Configuration
slug: /api/
---

```json title="default-configuration.json"
{
  "useClass": true,
  "useConstant": true,
  "useId": true,
  "useQuery": true,
  "useVariable": true,
  "minify": false
}
```

Each value enables their appropriate CSS rule and `minify` allows you to minify the output CSS.

## Changing the Configuration

:::caution
`setOpts` only creates a new SwordCSS instance with those options, it doesn't actually set the instances options.
:::

You can also change the configuration of a `SwordCSS` object.

```js
sword.setOpts({ ...newOpts });
```