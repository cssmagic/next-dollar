# Next-Dollar

> Use `$()` the future way.

## Concept

```js
// present
$('#wrapper li.active').find('a').text('Active Item').show()
```

```js
// future
import {find, text, show} from 'next-dollar'
let $ = document.querySelectorAll

$('#wrapper li.active')::find('a')::text('Active Item')::show()
```

***

## License

[MIT License](http://www.opensource.org/licenses/mit-license.php)
