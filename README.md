# command-extensions
Some extra Conan commands for different purposes, like artifactory tasks, conan-center-index, etc.

The commands present in this repository are *not* production ready, they are intended as an aiding guide,
but you'll probably want to create your own custom commands taking these as a base to ensure they meet your needs.

To install all the available commands, run `conan config install https://github.com/conan-io/command-extensions.git`,
and afterwards, running `conan --help` should show you all the custom commands available.

Those commands are:
 - `custom-commands:convert-txt-recipe`: Gets a `conanfile.txt` as input and returns its equivalent `conanfile.py`
