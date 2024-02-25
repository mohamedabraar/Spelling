# Spelling

Theoretically, on input of size *n*, an algorithm with a running time of *n* is “asymptotically equivalent,” in terms of *O*, to an algorithm with a running time of *2n*. Indeed, when describing the running time of an algorithm, we typically focus on the dominant (i.e., most impactful) term (i.e., *n* in this case, since *n* could be much larger than 2). In the real world, though, the fact of the matter is that *2n* feels twice as slow as *n*.

The challenge ahead of you is to implement the fastest spell checker you can! By “fastest,” though, we’re talking actual “wall-clock,” not asymptotic, time.

## Files
- `speller.c`: This program is designed to spell-check a file after loading a dictionary of words from disk into memory.
- `dictionary.c`: Contains the implementation for the dictionary.
- `dictionary.h`: Contains the prototypes for functions used in `dictionary.c`. Both `speller.c` and `dictionary.c` include this file for function declarations.

## Instructions
1. Implement the loading of the dictionary from disk into memory.
2. Implement the spell-checking functionality.
3. Ensure that your spell checker is efficient in terms of actual "wall-clock" time, not just asymptotic time complexity.

## Getting Started
1. Clone this repository.
2. Compile `speller.c`, `dictionary.c`, and link them together.
    ```
    make speller
    ```
3. Run the spell checker on a text file.
    ```
    ./speller text.txt
    ```

Feel free to explore the code and make improvements to create the fastest spell checker you can!

