### CFormInput

```jsx
import { CFormInput } from '@coreui/vue'
// or
import CFormInput from '@coreui/vue/src/components/form/CFormInput'
```

#### Props

| Prop name     | Description                                                                                                                                                                 | Type    | Values                                  | Default |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | --------------------------------------- | ------- |
| **disabled**  | Toggle the disabled state for the component.                                                                                                                                | boolean | -                                       |         |
| **invalid**   | Set component validation state to invalid.                                                                                                                                  | boolean | -                                       |         |
| **plainText** | Render the component styled as plain text. Removes the default form field styling and preserve the correct margin and padding. Recommend to use only along side `readonly`. | boolean | -                                       |         |
| **readonly**  | Toggle the readonly state for the component.                                                                                                                                | boolean | -                                       |         |
| **size**      | Size the component small or large.                                                                                                                                          | string  | `'sm' \| 'lg'`                          | -       |
| **type**      | Specifies the type of component.                                                                                                                                            | string  | `'color' \| 'file' \| 'text' \| string` | 'text'  |
| **valid**     | Set component validation state to valid.                                                                                                                                    | boolean | -                                       |         |