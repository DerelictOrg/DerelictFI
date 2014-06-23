DerelictFI
==========

A dynamic binding to the [FreeImage][1] library, version 3.15, for the D Programming Language.

For information on how to build DerelictFI and link it with your programs, please see the post [Using Derelict][2] at The One With D.

For information on how to load the FreeImage library via DerelictFI, see the page [DerelictUtil for Users][3] at the DerelictUtil Wiki. In the meantime, here's some sample code.

```D
import derelict.freeimage.freeimage;

void main() {
    // Load the FreeImagee library.
    DerelictFI.load();

    // Now FreeImage functions can be called.
    ...
}
```

[1]: http://freeimage.sourceforge.net/
[2]: http://dblog.aldacron.net/derelict-help/using-derelict/
[3]: https://github.com/DerelictOrg/DerelictUtil/wiki/DerelictUtil-for-Users