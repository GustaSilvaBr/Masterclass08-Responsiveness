# Responsiveness

## CSS Units

<br/>

### Fixed layout 
`px` - Pixels

### Fluid layout
`%` - Percentage

`auto` - Automatic

`vh` - Viewport Height

`vw` - Viewport Width

#

### Fixed texts
`1px` = 0.75pt
`16px` = 12pt;

### Fluid texts
`em` - Multiplied by parent tag
`rem` - Multiplied by root(html)

## Display Grid tricks

### template columns
`grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`

## Media queries

```css
    @media (max-width: 320px){
        #form h3{
            font-size: 2rem;
        }
    }
```
