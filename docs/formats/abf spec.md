# abf / mbf format

`.abf` and `.mbf` are different extensions, but the file format is the same.


All values are big endian integers.

Header:
First Byte: Width
Second Byte: Height
Third & Fourth Bytes: Mine Count

All remaining bytes are paired mine coordinates, with 0-based indexing.
First Byte: X
Second Byte: Y


The mine locations *should* be in sorted order (sorted on X, then Y), 
but I cannot guarantee this is the case for all clones.