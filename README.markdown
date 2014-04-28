# anyenv-exec

This is an [anyenv](https://github.com/riywo/anyenv) plugin that provides `anyenv exec` command to execute a `*env`'s sub-command with each installed `*env`.

## Installation

```sh
mkdir -p $(anyenv root)/plugins
git clone git://github.com/aereal/anyenv-exec.git $(anyenv root)/plugins/anyenv-exec
```

## Usage

### Show all *envs' version

```
anyenv exec --version
# plenv 2.1.1-9-g26dbef7
# pyenv 0.4.0-20140404-10-g601ac4b
# rbenv 0.4.0-97-gfe0b243
```

## License

MIT
