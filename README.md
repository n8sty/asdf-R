# asdf-R

[![Build Status](https://api.travis-ci.org/n8sty/asdf-R.svg?branch=master)](https://travis-ci.com/n8sty/asdf-R)

[R](https://www.r-project.org/) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add R https://github.com/iroddis/asdf-R.git
```

## ASDF options

Check [asdf](https://github.com/asdf-vm/asdf) for instructions on how to install and manage versions of R.

When installing R using `asdf install`, you can pass custom configure options with the following env vars:

* `R_CONFIGURE_OPTIONS` - use only your configure options
* `R_EXTRA_CONFIGURE_OPTIONS` - append these configure options along with ones that this plugin already uses

## Thanks

Thanks to [asdf-postgres](http://github.com/smashedtoatoms/asdf-postgres) for providing an awesome plugin
that was easy to modify for this language.

Thanks to the original author of this package [@iroddis](https://github.com/iroddis/) for the original
inspiration and doing the vast majority of the work.
