# Collagraph Syntax Highlight

**Note**: the `new` branch hosts the new syntax that only works in Sublime build > 3153. For the old syntax, see `master` branch.

Sublime Text Syntax highlighting for single-file [Collagraph](https://github.com/fork-tongue/collagraph) components.

<!-- TODO: update screenshot with Collagraph example -->
<p align="center">
  <img width="809px" src="https://raw.githubusercontent.com/vuejs/vue-syntax-highlight/new/samples/screenshot.png">
</p>


### Install

- Via Package Control: search for `Collagraph Syntax Highlight`.
- Manual: clone this repo into your Sublime `Packages` folder.


### Development

- The development of this syntax relies on the [YAML-Macros](https://github.com/Thom1729/YAML-Macros) package. You can install it from Package Control.
- Do not edit `Collagraph Component.sublime-syntax` directly. Work in `Collagraph Component.sublime-syntax.yaml-macros` instead. Once done editing, run "Build With: YAML Macros" from Sublime's command palette. This will update the actual `Collagraph Component.sublime-syntax` file.


### License

[MIT](http://opensource.org/licenses/MIT)
