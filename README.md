DerelictFI
==========

A dynamic binding to the [FreeImage][1] library, version 3.17, for the D Programming Language.

Please see the sections on [Compiling and Linking][2] and [The Derelict Loader][3], in the Derelict documentation, for information on how to build DerelictFI and load the FI libraries at run time. In the meantime, here's some sample code.

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
[2]: http://derelictorg.github.io/building/overview/
[3]: http://derelictorg.github.io/loading/loader/