# KIEN THUC

- gap trong grid su dung `gap: row-gap columns-gap` (same trong flex)
- khi don vi template cua grid khac `fr` thi width se = width + (gap)
- su dung track-line:

```css
grid-column: 1/3;
grid-row: 1/2;
grid-row: 1 / span 2;
grid-column: 2 / span2;
```

- voi `auto-fit` voi grid se co gang lap day khoang trong
- voi `auto-fill` chi co gang lap day cot

```css
grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
```
