# Why does this exist?

The `python@2` was (rightfully) removed from `homebrew-core` in [#48460](https://github.com/Homebrew/homebrew-core/pull/48460)

In order to maintain some legacy applications for my work, I have extracted the last iteration of the `python@2` formula to this repository. I will update it with the final 2.7.18 release once it is available.

# How do I use it?

Add the tap to homebrew:

`brew tap matt-chapman/python-2`

Install as usual:

`brew install python@2`

Because the binary bottles are no longer hosted by Homebrew, the formula will build from source.
