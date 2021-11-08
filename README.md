# nx

Forked from [comma](https://github.com/Shopify/comma)

`nx` runs software without installing it.

Basically it just wraps together `nix run` and `nix-index`. You stick a `nx` in front of a command to
run it from whatever location it happens to occupy in `nixpkgs` without really thinking about it.

## Installation

```bash
nix-env -i -f .
```

## Usage

```bash
nx cowsay neato
```
