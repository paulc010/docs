---
Title: displayAdditionalCustomerAddressFields
hidden: true
hookTitle: Display additional customer address fields
files:
    -
      theme: classic
      url: https://github.com/PrestaShop/classic-theme/blob/develop/templates/customer/_partials/block-address.tpl
      file: themes/classic/templates/customer/_partials/block-address.tpl
    -
      theme: hummingbird
      url: https://github.com/PrestaShop/hummingbird/blob/develop/templates/customer/_partials/block-address.tpl
      file: themes/hummingbird/templates/customer/_partials/block-address.tpl

locations:
    - front office
type: display
hookAliases: 
origin: theme
array_return: false
check_exceptions: false
chain: false
description: This hook allows to display extra field values added in an address form using hook 'displayAdditionalCustomerAddressFields'

---

{{% hookDescriptor %}}

## Call of the Hook in the origin file

```php
{hook h='displayAdditionalCustomerAddressFields' address=$address}
```
