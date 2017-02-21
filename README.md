# Money Format
Module for Drupal 7

Number to Money Format

## Example ##
100.00
```html
<div class="field-item even"><span class="money-label">$</span>100<span class="centavos">.00</span></div>
```

100.00
```html
<div class="field-item even"><span class="money-label">USD $</span>100<span class="centavos">.00</span></div>
```
100.00
```html
<div class="field-item even"><span class="money-label">S/.</span>100<span class="centavos">.00</span></div>
```
### Install ###
- Download module
- unzip in <drupal_site>/sites/all/modules/money_format
- Active module

For field chage format in Manage Display
## CSS ##
```css
.money-label {
    margin-right: 5px;
}
.centavos {
    font-size: 14px;
    text-decoration: underline;
    color: #797979;
    vertical-align: super;
    margin-left: 1px;
}
```
