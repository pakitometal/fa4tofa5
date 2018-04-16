# fa4tofa5
Translates FontAwesome 4.7.x class names to their equivalents in FontAwesome 5.0.x

# Usage
```console
fa4tofa5.php DIRECTORY [FILE_EXTENSION]
```
Scans recursively from DIRECTORY, searching in files matching FILE_EXTENSION (default "php")
for any FontAwesome 4.7 icon class name and replacing it with its FontAwesome 5.0 equivalent
according to the instructions found in <https://fontawesome.com/how-to-use/upgrading-from-4>.

## Project file list
* `fa4tofa5.php`: the translation script.
* `icon_index.txt`: 3-column text file with FA4 icon classnames and FA5 equivalents and prefixes.
* `icon_listing.ods`: OpenOffice Calc file with the same info as icon_index.txt, plus full FA5 to FA4 equivalence table.
* `LICENSE`: GNU GPL Version 3 license file
* `README.md`: this file.

# License
See the [LICENSE](LICENSE) file for license rights and limitations (GNU GPLv3).
