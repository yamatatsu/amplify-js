# amplify-email-field



<!-- Auto Generated Below -->


## Properties

| Property            | Attribute     | Description                                                                     | Type                          | Default             |
| ------------------- | ------------- | ------------------------------------------------------------------------------- | ----------------------------- | ------------------- |
| `fieldId`           | `field-id`    | Based on the type of field e.g. sign in, sign up, forgot password, etc.         | `string`                      | `EMAIL_SUFFIX`      |
| `handleInputChange` | --            | The callback, called when the input is modified by the user.                    | `(inputEvent: Event) => void` | `undefined`         |
| `label`             | `label`       | Used for the EMAIL label                                                        | `string`                      | `EMAIL_LABEL`       |
| `placeholder`       | `placeholder` | Used for the placeholder label                                                  | `string`                      | `EMAIL_PLACEHOLDER` |
| `required`          | `required`    | The required flag in order to make an input required prior to submitting a form | `boolean`                     | `false`             |
| `value`             | `value`       | The value of the content inside of the input field                              | `string`                      | `undefined`         |


## Dependencies

### Used by

 - [amplify-auth-fields](../amplify-auth-fields)

### Depends on

- [amplify-form-field](../amplify-form-field)

### Graph
```mermaid
graph TD;
  amplify-email-field --> amplify-form-field
  amplify-form-field --> amplify-label
  amplify-form-field --> amplify-input
  amplify-form-field --> amplify-hint
  amplify-auth-fields --> amplify-email-field
  style amplify-email-field fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*