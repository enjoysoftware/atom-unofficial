# Atom

Atom is a hackable text editor for the 21st century, built on [Electron](https://github.com/electron/electron), and based on everything we love about our favorite editors. We designed it to be deeply customizable, but still approachable using the default configuration.

![Atom](https://user-images.githubusercontent.com/378023/49132477-f4b77680-f31f-11e8-8357-ac6491761c6c.png)

![Atom Screenshot](https://user-images.githubusercontent.com/378023/49132478-f4b77680-f31f-11e8-9e10-e8454d8d9b7e.png)

## What is this repository different from official one?

* The Atom build script has been modified to work on the Raspberry Pi ARM. The build method is no different from the official one.


[Atom Official Website](https://atom.io)

[Author's blog(Japanese)](https://enjoysoftware.hatenablog.com)

## Building on Raspberry Pi and other Linux
If you want to build on Raspberry Pi, first, create a file in your home directory called .npmrc and add the following to that file:
```bash
arch=armv7l
```
After doing this, the method is the same as the official one.

* [Building on Linux](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-linux)


## License

[MIT](https://github.com/atom/atom/blob/master/LICENSE.md)

