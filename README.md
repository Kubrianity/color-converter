# color-converter
This is a color converter between different color models like hex,rgb and hsl. It also provides functionality for saturation and opposite colors.

## Usage

``` javascript

const red = new Color(255, 67, 89, 'red');

red.hsl();  // "hsl(353,100%, 63.1%)"

red.hex();  //  "#ff4359"

red.opposite(); // "hsl(173,100%, 63.1%)"

red.rgba(0.5);  // "rgba(255, 67, 89, 0.5)"

```
