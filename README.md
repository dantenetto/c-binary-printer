# C Binary Printer

This function is a simple binary_printer formated.

It can separate the bits in groups and can take several numbers
to print

### Format Codes
- `%c` = char to print (one byte)
- `%i` = int to print (four bytes)
- `%d` = delimiter in group (must be a char, defaults to `' '`)
- `%g` = number of bits in one group (must be a number)
- `%D` = delimiter for each binary string (must be a char)
 	if `%D` is not present, `%d` will be used as delimiter for a binary string
 	to avoid this, `%p` should the first letter for the string

#### Return Codes
- 1 if any memory error
- 0 if success