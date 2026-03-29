Command line arguments in C are passed by specifying: int main(int argc, char \*argv[]){}
this means that the main() function requires a number of *int argc* parameters in the *char \*array char \*argv[]*. *char \*argv[]* and *char \*\* argv* are the same.
The first parameter from argv[] is a pointer to the first string from the command line which contains the name of the binary program.

## Compilation process in C:
```
Source Code(.c, .h)
      |
      |
      V
 ------------
|Preprocessor|
 ------------
      |
      | Include Headersm Expand Macros(.i)
      V
 ----------
|Compiation|
 ----------
    |
    | Assembly Code(.s)
    V
 --------
|Assembly|
 --------
    |
    | Object Code(.o)
    V
 -------
|Linking|  <---Static Libraries(.lib, .a)
 -------
    |
    |
    V
Executable code(.x)
```
