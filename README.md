# Mic-1 in Digital

This is an implementation of the Mic-1 architecture from [Structured Computer Architechture, 6th Ed. by Andrew S. Tanenbaum](https://csc-knu.github.io/sys-prog/books/Andrew%20S.%20Tanenbaum%20-%20Structured%20Computer%20Organization.pdf) in the [Digital](https://github.com/hneemann/Digital) Logic simulator by [hneemann](https://github.com/hneemann).

All IJVM instructions are implemented in MAL, although i do not guarantee that it is without issues. I used my hacked together [MAL compiler](https://github.com/gamemode-3/mal-compiler) to translate from MAL-adjacent code into the corresponding control store bits.

You need to initialize the storage or it will be all zeros.

![Screenshot of the Mic-1](https://github.com/gamemode-3/Digital-Mic-1/blob/main/assets/Screenshot%20from%202024-02-21%2014-32-45.png)