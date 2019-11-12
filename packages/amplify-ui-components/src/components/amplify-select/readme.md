# amplify-select



<!-- Auto Generated Below -->


## Properties

| Property        | Attribute        | Description                                                                                                                 | Type                                             | Default                 |
| --------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ----------------------- |
| `fieldId`       | `field-id`       | Used for id field                                                                                                           | `string`                                         | `undefined`             |
| `options`       | --               | The options of the select input. Must be an Array of Objects with an Object shape of {label: string, value: string\|number} | `SelectOptions<number> \| SelectOptions<string>` | `DEFAULT_SELECT_OPTION` |
| `overrideStyle` | `override-style` | (Optional) Overrides default styling                                                                                        | `boolean`                                        | `false`                 |


## Dependencies

### Used by

 - [amplify-country-dial-code](../amplify-country-dial-code)
 - [amplify-examples](../amplify-examples)

### Graph
```mermaid
graph TD;
  amplify-country-dial-code --> amplify-select
  amplify-examples --> amplify-select
  style amplify-select fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*