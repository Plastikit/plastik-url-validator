plastik-url-validator
============

`plastik-url-validator` checks whether or not any input is a valid URL.

This functionality is provided by the [validator.js](https://github.com/chriso/validator.js)
library, a dependency of this element.

Demos and documentation are available on the 
[component page](http://www.plastikit.org/1.x/#!/components/plastik-url-validator/).

Pull requests are always welcome. If you encounter any bugs, please feel free to
[submit an issue](https://github.com/Plastikit/plastik-url-validator/issues/new/).

## Installation

```sh
bower install Plastikit/plastik-url-validator --save
```

## Basic usage

 > _See [component page](http://www.plastikit.org/1.x/#!/components/plastik-url-validator/)
 > for more details._

### Example

```html
<input is="iron-input" bind-value="{{value}}" validator="plastik-url-validator">

<plastik-url-validator protocol-optional allow-protocol-relative-urls>
</plastik-url-validator>
```
