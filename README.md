# Identicon

My first project with elixir and functional programming.

It generates a 250x250 png identicon image.

## Usage

Make sure you have elixir/erlang installed and up to date, then clone this repository.

```
$ cd identicon
$ iex -S mix
iex> Identicon.main('your string here')
```

A png image will be outputed in source folder nammed after the string you passed as the argument.
