# modulemd\_add\_platform

This tool edits a modulemd-packager YAML document.
It copies contexts of an old platform to new contexts of a new platform.
A file with the modulemd-packager YAML document is overrided.
If a context for the new platform already exists, nothing is done.
If a context for the old platform does not exist, an error is reported.