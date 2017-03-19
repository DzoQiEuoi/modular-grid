# Modular Grid

A bootstrap-style grid for use with CSS Modules

## Example usage

```
myClass {
    composes: col-md-4 from 'modular-grid';
}
```
## Available Classes

- container
- row
- col-[breakpoint]-[columns]
- col-[breakpoint]-offset-[columns]
- col-[breakpoint]-push-[columns]
- col-[breakpoint]-pull-[columns]
- visible-from-[breakpoint]
- visible-until-[breakpoint]
- hidden-from-[breakpoint]
- hidden-until-[breakpoint]

## Customise

The number of columns, gutter size, and breakpoints are all controlled by Sass variables with the `!default` flag so you can overide these with your own values.

### Example

```
$gutter: 20px;
$columns: 8;
$breakpoints: (xs: 0px, sm: 400px, md: 800px, lg: 1200px);
```