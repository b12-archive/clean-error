[![Coveralls – test coverage
](https://img.shields.io/coveralls/studio-b12/clean-error.svg?style=flat-square)
](https://coveralls.io/r/studio-b12/clean-error)
 [![Travis – build status
](https://img.shields.io/travis/studio-b12/clean-error/master.svg?style=flat-square)
](https://travis-ci.org/studio-b12/clean-error)
 [![David – status of dependencies
](https://img.shields.io/david/studio-b12/clean-error.svg?style=flat-square)
](https://david-dm.org/studio-b12/clean-error)
 [![Stability: experimental
](https://img.shields.io/badge/stability-experimental-yellow.svg?style=flat-square)
](https://nodejs.org/api/documentation.html#documentation_stability_index)
 [![Code style: airbnb
](https://img.shields.io/badge/code%20style-airbnb-blue.svg?style=flat-square)
](https://github.com/airbnb/javascript)




clean-error
===========

**Never worry about catching errors again.**  
A tiny wrapper around *[tiny-error][]*.

[tiny-error]:  http://npm.im/tiny-error




<p align="center"><a
  title="Graphic by the great Justin Mezzell"
  href="http://justinmezzell.tumblr.com/post/66281274442"
  >
  <br/>
  <br/>
  <img
    src="Readme/Fun.gif"
    width="400"
    height="300"
  />
  <br/>
  <br/>
</a></p>




Demo
----

Catching errors to print a message to the user? Don’t bother! Just throw them and let them halt your program. They’ll still look pretty darn clean.


You write:

```js
const cleanError = require('clean-error')('my-amazing-program');

throw cleanError('Oops!');
```


The user sees:

*Coming soon…*




Installation
------------

```sh
$ npm install clean-error
```




License
-------

[MIT][] © [Studio B12 GmbH][]

[MIT]:              ./License.md
[Studio B12 GmbH]:  http://studio-b12.de
