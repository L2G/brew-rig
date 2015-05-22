# brew-rig

```
brew install mr
git clone git://github.com/L2G/brew-rig.git homebrew
cd homebrew
mr checkout
```

Then, to use these checkouts as a development environment (assuming Bash in
use):

```
. _dev_env
```

This does two things:
* it replaces references to `/usr/local` in your PATH with references to your
  local brew-rig checkout; and
* it sets the `HOMEBREW\_BREW\_FROM\_SOURCE` environment variable so that
  Homebrew always builds from source instead of downloading bottles.
