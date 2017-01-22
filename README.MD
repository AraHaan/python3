# Notes

Installing Python:

When you install Python 3.4.3 after python 3.4.2 then python 3.4.2 would be overwritten.

It is the same for everything in the 3.4.x, 3.5.x, and 3.6.x series. If you need to
test multiple versions of each major release then do all the tests before using homebrew
to install the next minor release.

Note: it might take a while to compile each release of python.

You might need to set up travis to cache the builds of python so you dont have to do this every Pull request or push.

(That is if you are using this for travis.)

# Example

Here is an example usage of using this Repo with Homebrew:

```cmd
brew tap AraHaan/python3
brew install python342
// Use Python 3.4.2 for testing stuff.
brew install python343
// Use Python 3.4.3 for testing stuff.
brew install python344
// Use Python 3.4.4 for testing stuff.
brew install python345
// Use Python 3.4.5 for testing stuff.
brew install python346
// Use Python 3.4.6 for testing stuff.
brew install python350
// Use Python 3.5.0 for testing stuff.
brew install python351
// Use Python 3.5.1 for testing stuff.
brew install python352
// Use Python 3.5.2 for testing stuff.
brew install python353
// Use Python 3.5.3 for testing stuff.
brew install python360
// Use Python 3.6.0 for testing stuff.
```

Note: Nightly build of Python 3.7 is not available yet. The "tarballs" are directly downloaded from Python's CDN
that hosts not only sources archives but also installer msi's for Windows.
