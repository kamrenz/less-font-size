# less-font-size
Less font-size mixin for allowing rem to fallback to pixel

## Need to know
This is based on the `<html>` tag having a `font-size: 62.5%` for easy rem to pixel conversion.

## How to use
* Less code to utilize mixin  
`.font-size(1rem);`
* Generated CSS code from the mixin  
`font-size: 30px;`  
`font-size: 3rem;`