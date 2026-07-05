# Number Systems (Binary, Decimal & Hexadecimal)

## What I Learned

Computers don't understand decimal numbers like humans do. They only understand **binary (base 2)** because electronic components (transistors) have only two stable states:

- `0` → OFF (Low Voltage)
- `1` → ON (High Voltage)

Everything inside a computer (numbers, text, images, videos, etc.) is stored using binary.

## Number Systems

| Number System | Base | Digits |
|---------------|------|--------|
| Binary | 2 | 0, 1 |
| Octal | 8 | 0–7 |
| Decimal | 10 | 0–9 |
| Hexadecimal | 16 | 0–9, A–F |

## Decimal (Base 10)

Each digit represents a power of 10.

Example:

```
213

= 2 × 10² + 1 × 10¹ + 3 × 10⁰

= 200 + 10 + 3

= 213
```

## Binary (Base 2)

In binary, each digit represents a power of 2.

### Powers of 2

| Power | Value |
|-------|------:|
| 2⁰ | 1 |
| 2¹ | 2 |
| 2² | 4 |
| 2³ | 8 |
| 2⁴ | 16 |
| 2⁵ | 32 |
| 2⁶ | 64 |
| 2⁷ | 128 |

### Binary to Decimal

Example:

```
1001₂

= 1 × 2³ + 0 × 2² + 0 × 2¹ + 1 × 2⁰

= 8 + 0 + 0 + 1

= 9
```

Another example:

```
1101₂

= 8 + 4 + 0 + 1

= 13
```


## Bits and Bytes

- **1 Bit** = A single binary digit (`0` or `1`)
- **8 Bits** = **1 Byte**

A byte can store:

```
2⁸ = 256 values

0 to 255
```

## Hexadecimal (Base 16)

Hexadecimal is just a shorter and easier way to write binary.

One hexadecimal digit represents **4 bits**.

### Binary to Hex Table

| Binary | Hex |
|:------:|:---:|
|0000|0|
|0001|1|
|0010|2|
|0011|3|
|0100|4|
|0101|5|
|0110|6|
|0111|7|
|1000|8|
|1001|9|
|1010|A|
|1011|B|
|1100|C|
|1101|D|
|1110|E|
|1111|F|

```
A = 10
B = 11
C = 12
D = 13
E = 14
F = 15
```

## Binary to Hex Example

```
101000111110101000101010

↓

1010 0011 1110 1010 0010 1010

↓

 A    3    E    A    2    A

Answer = A3EA2A
```

## Hex to Decimal Example

```
9BDF₁₆

= 9 × 16³
+ 11 × 16²
+ 13 × 16¹
+ 15 × 16⁰

= 39903₁₀
```

## RGB Colors

Modern computers use **24-bit color**.

Each color is made up of:

- 1 Byte → Red
- 1 Byte → Green
- 1 Byte → Blue

So,

```
8 + 8 + 8 = 24 bits
```

Each color can have **256 intensity levels (0–255)**.

Total possible colors:

```
256 × 256 × 256

= 16,777,216 colors
```

Some examples:

| Hex Code | Color |
|----------|-------|
| #000000 | Black |
| #FFFFFF | White |
| #FF0000 | Red |
| #00FF00 | Green |
| #0000FF | Blue |

## Why Hexadecimal?

Binary numbers become very long and difficult to read.

Instead of writing:

```
110101111001011010100111
```

we can simply write:

```
D796A7
```

This makes it much easier for humans to read and work with.

## Why is this important in Cybersecurity?

Hexadecimal is used everywhere in cybersecurity, such as:

- Memory addresses
- Packet captures (Wireshark)
- File signatures
- Hashes (MD5, SHA-256)
- Malware analysis
- Reverse engineering

So understanding binary and hexadecimal is very important.

## Summary

- Computers use **binary (base 2)**.
- Humans normally use **decimal (base 10)**.
- Hexadecimal is **base 16**.
- **1 Bit = 0 or 1**
- **8 Bits = 1 Byte**
- **1 Hex Digit = 4 Bits**
- **1 Byte = 2 Hex Digits**
- RGB colors use **24 bits (3 bytes)**.
- 24-bit color can represent **16,777,216 colors**.
