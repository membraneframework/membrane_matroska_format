# Membrane Matroska Format

[![Hex.pm](https://img.shields.io/hexpm/v/membrane_matroska_format.svg)](https://hex.pm/packages/membrane_matroska_format)
[![API Docs](https://img.shields.io/badge/api-docs-yellow.svg?style=flat)](https://hexdocs.pm/membrane_matroska_format)
[![CircleCI](https://circleci.com/gh/membraneframework/membrane_matroska_format.svg?style=svg)](https://circleci.com/gh/membraneframework/membrane_matroska_format)

This package provides structures describing Matroska format. They can be used to define capabilities of pads for the [Membrane](https://membraneframework.org) Elements.

## Installation

Unless you're developing an Membrane Element it's unlikely that you need to use this package directly in your app, as normally it is going to be fetched as a dependency of any element that operates on Matroska file.

However, if you are developing an Element or need to add it due to any other reason, just add the following line to your `deps` in the `mix.exs` and run `mix deps.get`.

```elixir
def deps do
  [
    {:membrane_matroska_format, "~> 0.1.0"}
  ]
end
```


## Copyright and License

Copyright 2022, [Software Mansion](https://swmansion.com/?utm_source=git&utm_medium=readme&utm_campaign=membrane_matroska_format)

[![Software Mansion](https://logo.swmansion.com/logo?color=white&variant=desktop&width=200&tag=membrane-github)](https://swmansion.com/?utm_source=git&utm_medium=readme&utm_campaign=membrane_matroska_format)

Licensed under the [Apache License, Version 2.0](LICENSE)
