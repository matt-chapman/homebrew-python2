# Python@2 Homebrew Tap

## Why does this exist?

The `python@2` was removed from `homebrew-core` in [#49796](https://github.com/Homebrew/homebrew-core/pull/49796), as Python 2.7.x is now [EOL](https://www.python.org/dev/peps/pep-0373/#id4) and should no longer be in general usage.

In order to maintain some legacy applications for my work, I have extracted the last iteration of the `python@2` formula to this repository. It has since been updated with [Python 2.7.18](https://www.python.org/downloads/release/python-2718/), the last release (ever!) for Python 2.7.

You should _not_ be using this for any new projects. This is a deprecated formula, and exists here only to facilitate running and supporting software that depends on it.

## How do I use it?

### Installation

Add the tap to homebrew:

`brew tap matt-chapman/python2`

Install as usual:

`brew install python@2`

Because the binary bottles are no longer hosted by Homebrew, the formula will build from source.

### Uninstallation

To uninstall:

`brew uninstall python@2`

To remove this tap:

`brew untap matt-chapman/python2`
