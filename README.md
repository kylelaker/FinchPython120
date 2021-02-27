# Finch Python

This is a mirror of sorts of the
[Finch 1 Python code](https://www.birdbraintechnologies.com/finch1/python/install/) which per
the README.txt distributed with the ZIP file is licensed under the MIT license. See
[LICENSE.txt](LICENSE.txt).

In the past, Bird Brain Technologies has released new versions of the code under the same file
name, FinchPython120.zip, with no way to identify what changed between versions. This repository
will generally try to pull each version of the code as a commit and as a tag to try to give some
sort of idea of what has changed.

## Versions

"Versions" will be named with the date the version was first seen in YYYYMMDD format. In the event
two or more versions are released on the same day, subsequent releases will get an appended letter
starting with `a`.

The earliest version of code available is from October 24, 2019.

## Compared to upstream

This repo will strip the `__pycache__` folder, any `__MACOSX` folders, or other files that would
generally not get committed or distributed with project code. Otherwise, it is not an intention to
modify any other code.

This README.md file is also included, which is not part of the upstream distribution.
