# wla-vim

This plugin offers syntax highlighting for 6502/65816 assembly code to be compiled with WLA-DX. If you're only using it for 6502 code, it will not warn you when you are using a 65C02- or 65816-only instruction, and it will highlight it as if it were a valid instruction (I'm too dumb to actually check for things like that).

With Lunar Vim (which I use and can recommend), you can install this plugin by including `AmNotOnline/wla-nvim` in your `lvim.plugins` list like so:

```lua
lvim.plugins = {
    ...
    { "AmNotOnline/wla-nvim" },
    ...
}
```
