# Encoding scheme for strings

Two common formats used for encoding strings are:
 * ASCII
 * Unicode


## ASCII
American National Standard Code for Information Interchange

Ascii is a 7-bit character set, so their are 2^7 unique ascii values.

These numbers are broken up into two general types of codes:
 * 31 are "Control" codes (control features of the stdout)

Encodng scheme for strings (characters)

* In 8 bit computing the 8th bit can be used (or used as a parity bit for error checking)


## Extended ASCII character sets

* Because 8 bit computers allowed for 256 characters and symbols of the english language.

* When other nations wanted to use they needed code points to assign to their own alphabets. This space was found by using the additional 8th bit.

* Characters sets that used the 8th bit were known as extended ascii.

* each version of extended ASCII differs from other versions.



## Unicode
Emojis 🚀🚀🚀

 * A worldwide character-encoding standard.

 * It's main objective is to enable a single, unique character set that is capable of supporting all characters from all scripts, as well as symbols.

 * Unicode is an extension of ASCII.

 * Unicode implements variable width encoding.

 * Variable- width encoding is a type of character encoding scheme in which codes of differing lengths are used to encode codes of differing lengths.


## UTF - Unicode Transformation Format

UTF-8 is a method of encoding Unicode characters and it is the main encoding method used for this on the internet. The 8 means it uses 8-bit blocks to represent characters on the internet.

Worked encoding example:
```

U+20AC

C - 1100

12

A - 1010


0 - 0000

2 - 0010

0x20AC - 10000010101100

11100010 10000010 10101100


```

worked decoding value:


```

11100010 10000010 10101100

111 - first three bits indicate a 3 byte sequence

remove the first four bytes of the first bit and the first two of the preceding values

0010 000010 101100

I convert it to base 16 -> U+20AC - €

```








