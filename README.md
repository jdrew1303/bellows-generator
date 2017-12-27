<a name="module_bellows"></a>

## bellows
**Example**  
```js
const bellows = require('bellows')
```
<a name="module_bellows..bellows"></a>

### bellows~bellows([options])
Generate bellows pattern for cutting and folding.

**Kind**: inner method of [<code>bellows</code>](#module_bellows)  

| Param | Type | Description |
| --- | --- | --- |
| [options] | <code>Object</code> | Bellows configuration options |
| [options.dpi] | <code>Integer</code> | DPI of the image |
| [options.pageW] | <code>Integer</code> | Page width in pixels |
| [options.pageH] | <code>Integer</code> | Page height in pixels |
| [options.frontIW] | <code>Integer</code> | Front inner width of bellows in pixels |
| [options.frontOW] | <code>Integer</code> | Front outer width of bellows in pixels |
| [options.frontIH] | <code>Integer</code> | Front inner height of bellows in pixels |
| [options.frontOH] | <code>Integer</code> | Front outer height of bellows in pixels |
| [options.backIW] | <code>Integer</code> | Back inner width of bellows in pixels |
| [options.backOW] | <code>Integer</code> | Back outer width of bellows in pixels |
| [options.backIH] | <code>Integer</code> | Back inner height of bellows in pixels |
| [options.backOH] | <code>Integer</code> | Back outer height of bellows in pixels |
| [options.maxLength] | <code>Integer</code> | Maximum length of bellows in pixels |
| [options.align] | <code>Integer</code> | Vertical alignment adjustment in pixels |
| [options.parts] | <code>Integer</code> | Number of parts to split pattern into: 1, 2, or 4 returns {String}  Base64 encoded png data |

**Example**  
Generate the default square bellows in 2 parts and print the string to the console.
```
const b = bellows({ parts : 2 })
console.log(b)
```