# Plurimath-JS

A JavaScript converter of mathematical formulas

## Building

### The easy method

Please make sure you have podman installed and do `npm run submodule:init` and then `npm run build`.

### The developer method

It is recommended to use Docker/Podman to get a compatible environment.
As of now, it is needed to use Ragel 6 to build necessary parsers.

```bash
$ podman build -t plurimath-js .
$ podman run --rm -it -v.:/srv:z plurimath-js

Inside Podman shell:

# cd /srv
# ./setup.sh
# ./build.sh
```

## Demo

Demo is available [here](https://plurimath-js.github.io/plurimath-js/demo.html)
