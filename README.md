# Elixir Rsync

## Install

```bash
$ npm install elixir-rsync --save-dev
```

## Usage

### Example `gulpfile.js`

```js
var elixir = require( 'laravel-elixir' );

require( 'elixir-rsync' );

elixir( function( mix )
{
    mix.rsync( 'theme/src/', 'public/theme' );
});
```

### Advanced Example

```js
var elixir = require( 'laravel-elixir' );

require( 'elixir-rsync' );

elixir( function( mix )
{
    mix.rsync( 'theme/src/', 'public/theme', '-rc --delete' );
});
```

# License

[MIT](/LICENSE)
