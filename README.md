# Carbon Spice VSCode

Carbon spice is an attempt to create a colorscheme that has good contrast and
readability along with meaningful highlights for code editing.

It is based on [IBM's design language](https://www.ibm.com/design/language/color/) 
and their [Carbon Gray100 colors](https://carbondesignsystem.com/guidelines/color/usage/).

The codebase is based off of Marvin Engelmann's [IBM theme]
(https://github.com/marvinengelmann/vscode-ibm-theme).
In addition to it already having set some of the UI colors following the IBM guidelines,
I liked the way that tokens were split by color name. This will make it much easier to template
the colortheme in the future as well.

This is very much a Work In Progress and there will be many inconsistencies to
start with.

## Syntax Colors

| Color name       |Color Code | Main use                | 
|------------------|---------- |-------------------------| 
| Gray 10          | `#f4f4f4` | Variables and Foreground|
| Cyan 40          | `#33b1ff` | Keywords                |
| Alert 40         | `#ff832b` | Functions               |
| Green 40         | `#42be65` | Strings                 |
| Magenta 40       | `#ff7eb6` | Constants               |
| Purple 40        | `#be95ff` | Types                   |
| Teal 40          | `#08bdba` | Comments and Operators  |

## Screenshot

Font is IBM Plex Mono.

![Rust+Terminal](/CarbonSpice_Rust.png)