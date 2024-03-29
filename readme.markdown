# gamma

[gamma function](http://en.wikipedia.org/wiki/Gamma_function)
in javascript using the
[lanczos approximation](http://en.wikipedia.org/wiki/Lanczos_approximation)
for small values and the 
[spouge approximation](https://en.wikipedia.org/wiki/Spouge's_approximation) for
larger values

# example

```
> import gamma from 'gamma'
> gamma(5)
23.999999999999996
> gamma(1.6)
0.8935153492876909
```

# methods

import gamma from 'gamma'

## gamma(z)

Return the gamma function over `z`. Complex numbers aren't supported, only reals.

## log(z)

```
import { log } from 'gamma'
```

Return the natural log of the gamma function for `z`.

This function is used internally by the spouge approximation to compute large
values.

# install

With [npm](http://npmjs.org) do:

```
npm install @qubyte/gamma
```

# kudos

Implementation transliterated from the python script on the wikipedia entry for
the
[lanczos approximation](http://en.wikipedia.org/wiki/Lanczos_approximation).

Spouge approximation from [Niggler](https://github.com/Niggler).

# license

MIT
