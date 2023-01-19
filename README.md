<h1 align=center>css-tricks</h1>

https://css-tricks.com/a-complete-guide-to-data-attributes/


```css
/* Selects if the attribute is present at all */
[data-size] { }

/* Selects if the attribute has a particular value */
[data-state="open"],
[aria-expanded="true"] { }

/* "Starts with" selector, meaning this would match "3" or anything starting with 3, like "3.14" */
[data-version^="3"] { }

/* "Contains" meaning if the value has the string anywhere inside it */
[data-company*="google"] { }
```


```php
<?php echo
