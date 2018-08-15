# pass2csv
Needs [python-gnupg](https://pypi.python.org/pypi/python-gnupg). Run with path
to password store as argument.

The csv is written to `pass.csv`. The format for KeePassXC importer is:

`Group(/),Title,User,Password,URL,Notes`

Where 'Password' is the first line of the entry in `pass` and 'Notes' are all
subsequent lines. '\\' should not be interpreted as an escape character.
