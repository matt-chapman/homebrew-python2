# Python@2 Homebrew Tap

## Why does this exist?

The `python@2` was (rightfully) removed from `homebrew-core` in [#48460](https://github.com/Homebrew/homebrew-core/pull/48460), as Python 2.7.x is now [EOL](https://www.python.org/dev/peps/pep-0373/#id4)

In order to maintain some legacy applications for my work, I have extracted the last iteration of the `python@2` formula to this repository. I will update it with the final 2.7.18 release once it is available.

You should _not_ be using this for any new projects. This is a deprecated formula, and exists here only to facilitate running and supporting software that depends on it.

## How do I use it?

### Installation

Add the tap to homebrew:

`brew tap matt-chapman/python-2`

Install as usual:

`brew install python@2`

Because the binary bottles are no longer hosted by Homebrew, the formula will build from source.

### Uninstallation

To uninstall:

`brew uninstall python@2`

To remove this tap:

`brew untap matt-chapman/python-2`
