# Length In Bytes

## Instructions

Write a function called `byteSize` that takes a string as input and returns the size of the string in bytes. The function should work for both ASCII and non-ASCII characters.

## Examples

```
byteSize('hello world'); // expected output: 11
byteSize('안녕하세요'); // expected output: 15
byteSize(''); // expected output: 0
```

## Acceptance Criteria

- When the `byteSize` function is called with a string input, it should return the size of the string in bytes.
- The function should work for both ASCII and non-ASCII characters.
- The function should handle empty string input and return a byte size of 0.
