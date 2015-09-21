# npm-prev

Wraps the previous stable version of npm as an executable `npm-prev`.

Allows you to use previous stable npm alongside whatever other version of `npm` you currently have installed.

## Installation & Update

```
npm install -g npm-prev
```

Remember to run this semi-regularly to get the latest version of npm v3.

Make sure you understand what's changing in npm v3 by reading the excellent [Release Notes](https://github.com/npm/npm/releases).

## Usage

The `npm-prev` executable behaves exactly like `npm`:

```
> npm-prev -v
2.14.5
> npm-prev install
> npm-prev search
# etc
```

## See Also

* [npm-next](https://github.com/timoxley/npm-next)
* [npm3](https://github.com/timoxley/npm3)

# License

MIT
