# mgpu
Developed by [The Duat](https://theduat.neocities.org).
## Hybrid graphics manager

This tool lets you specify what GPU you want a command to run on.

- `mgpu -d commandhere` - Runs the command given on your dedicated gpu.
- `mgpu -i commandhere` - Runs the command given on your integrated gpu.

Example: 
- `mgpu -d glxgears` - This will run glxgears on your dedicated gpu.

## How to install

1. Install the `lua` and `git` packages provided by your distro.
2. Run `git clone https://github.com/Mizosu97/mgpu && cd mgpu && ./install`
