# C Programming Basics

## 1. Data Types

| Data Type | Description |
|---|---|
| int | Stores whole numbers |
| float | Stores decimal numbers |
| double | Stores decimal numbers with higher precision |
| char | Stores a single character |
| bool | Stores true or false |
| void | Represents no value |

## 2. Format Specifiers

| Format Specifier | Description |

| %d | Integer |
| %u | Unsigned integer |
| %o | Octal |
| %x | Hexadecimal lowercase |
| %X | Hexadecimal uppercase |
| %f | Floating-point value |
| %e | Scientific notation |
| %c | Character |
| %s | String |
| %ld | Long integer |

## 3. Input/Output Functions

| Function | Description |

| scanf() | Takes formatted input from the user |
| printf() | Displays formatted output |
| getchar() | Reads one character |
| putchar() | Displays one character |
| fgets() | Reads a string, including spaces |
| puts() | Displays a string |

## 4. Escape Sequences

| Escape Sequence | Meaning |

| \n | New line |
| \t | Tab |
| \\ | Backslash |
| \" | Double quotation mark |
| \' | Single quotation mark |

## 5. Precision

Precision specifies how many digits are displayed after the decimal point for a floating-point value.

Examples:

%.2f displays 2 digits after the decimal point.

%.4f displays 4 digits after the decimal point.

%.6f displays 6 digits after the decimal point.

Example:

printf("%.2f", value);

