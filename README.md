# Advanced Text Editor with AVL Tree Storage, Spell Checking, and Huffman Coding Compression

This repository contains a text editor that supports AVL tree-based word storage, spell checking, and Huffman coding-based compression. The text editor allows users to insert, replace, and delete words while maintaining a balanced AVL tree structure. Additionally, it offers spell checking and text compression functionalities.

## Features

- **AVL Tree-Based Word Storage:** Efficiently manage and maintain words in a balanced AVL tree structure.
- **Spell Checker:** Check the spelling of words using a custom spell checker with a tolerance level for edit distance.
- **Huffman Coding-Based Compression:** Encode and decode text using Huffman coding to achieve compression.

## Getting Started

### Prerequisites

To compile and run this program, you will need:

- A C++ compiler supporting C++11 or later.
- `make` (optional, for using the provided Makefile).

### Usage

Upon running the program, you will be prompted to enter commands:

1. **Insert a word:**
    - Enter `1` to insert a word.
    - You will be prompted to enter the word to insert.
    - Optionally, perform a spell check for the inserted word.

2. **Replace a word:**
    - Enter `2` to replace a word.
    - You will be prompted to enter the old word and the new word.

3. **Delete a word:**
    - Enter `3` to delete a word.
    - You will be prompted to enter the word to delete.

4. **Exit and Encode/Decode Text:**
    - Enter `4` to exit.
    - The program will display the sentence formed from the words in the AVL tree.
    - It will then encode and decode the sentence using Huffman coding.
    - The original size, encoded size, and compression ratio will be displayed.
    - Encoded and decoded data will be saved to `encode.txt` and `decode.txt` respectively.

### Example Input File

The input file `input.txt` should contain a list of words to load into the spell checker dictionary, one word per line.

### Output Files

- `encode.txt`: Contains the encoded string using Huffman coding.
- `decode.txt`: Contains the decoded string after Huffman decoding.


### Acknowledgments

- AVL Tree implementation and balancing logic.
- Huffman Coding implementation for text compression.
- Spell Checker with edit distance tolerance.
