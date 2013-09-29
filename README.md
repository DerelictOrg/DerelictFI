DerelictFI
==========

A dynamic binding to the [FreeImage](http://freeimage.sourceforge.net/) library, version 3.15, for the D Programming Language.

For information on how to build DerelictFI and link it with your programs, please see the post [Building and Using Packages in DerelictOrg](http://dblog.aldacron.net/forum/index.php?topic=841.0) at the Derelict forums.

For information on how to load the FreeImage library via DerelictFT, see the page [DerelictUtil for Users](https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users) at the DerelictUtil Wiki. In the meantime, here's some sample code.

```D
import derelict.freeimage.freeimage;

void main() {
    // Load the FreeImagee library.
    DerelictFI.load();

    // Now FreeType functions can be called.
    ...
}
```