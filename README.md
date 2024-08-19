# String Manipulation Library in C++

This repository contains a C++ class, `clsString`, that provides a robust set of string manipulation functions. It simplifies many common string operations, making it a valuable tool for C++ developers.

## Features

- **Count Words and Letters**: Count the number of words, capital letters, small letters, vowels, and specific characters in a string.
- **Case Conversion**: Convert the first letter of each word to uppercase or lowercase, convert the entire string to uppercase or lowercase, and invert the case of all letters.
- **String Trimming**: Trim whitespace from the left, right, or both ends of a string.
- **Splitting and Joining**: Split a string into a vector of substrings based on a delimiter, and join a vector of strings into a single string.
- **Advanced Operations**: Replace words in a string, reverse the order of words, and remove punctuations.

## Usage

```cpp
#include "clsString.h"

int main() {
    clsString myString("Hello, World!");

    myString.upperAllString();
    cout << myString.value << endl;

    myString.trim();
    cout << myString.value << endl;

    cout << "Word Count: " << myString.countWords() << endl;

    return 0;
}
