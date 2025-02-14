---
layout: ../../layouts/BlogLayout.astro
title: "C# Cheatsheet"
---

C Sharp is a general-purpose, multi-paradigm programming language encompassing strong typing, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines. It was developed around 2000 by Microsoft within its .NET initiative and later approved as a standard by Ecma (ECMA-334) and ISO (ISO/IEC 23270:2018). C# is one of the programming languages designed for the Common Language Infrastructure.
**[🔼Back to Top](#table-of-contents)**

## Data Types

| Data Type | Description                     | Size     |
| --------- | ------------------------------- | -------- |
| bool      | Boolean data type               | 1 bit    |
| byte      | Unsigned integer                | 1 byte   |
| char      | Character                       | 2 bytes  |
| decimal   | Decimal data type               | 16 bytes |
| double    | Double-precision floating point | 8 bytes  |
| float     | Single-precision floating point | 4 bytes  |
| int       | Integer                         | 4 bytes  |
| long      | Long integer                    | 8 bytes  |
| sbyte     | Signed integer                  | 1 byte   |
| short     | Short integer                   | 2 bytes  |
| uint      | Unsigned integer                | 4 bytes  |
| ulong     | Unsigned long integer           | 8 bytes  |
| ushort    | Unsigned short integer          | 2 bytes  |

**[🔼Back to Top](#table-of-contents)**

## Variables

Variables are containers for storing data values.

```csharp
int myNum = 5;               // Integer (whole number)

double myFloatNum = 5.99D;   // Floating point number

char myLetter = 'D';         // Character

string myText = "Hello";     // String

bool myBool = true;          // Boolean
```

**[🔼Back to Top](#table-of-contents)**

## Operators

| Operator | Description    | Example |
| -------- | -------------- | ------- |
| +        | Addition       | x + y   |
| -        | Subtraction    | x - y   |
| \*       | Multiplication | x \* y  |
| /        | Division       | x / y   |
| %        | Modulus        | x % y   |
| ++       | Increment      | ++x     |
| --       | Decrement      | --x     |

**[🔼Back to Top](#table-of-contents)**

## Loops

### For Loop

```csharp
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

### While Loop

```csharp
while (condition) {
  // code block to be executed
}
```

### Do While Loop

```csharp
do {
  // code block to be executed
}
while (condition);
```

### For Each Loop

```csharp
foreach (type variableName in arrayName) {
  // code block to be executed
}
```

### Break

```csharp
for (int i = 0; i < 10; i++) {
  if (i == 4) {
    break;
  }
  Console.WriteLine(i);
}
```

### Continue

```csharp
for (int i = 0; i < 10; i++) {
  if (i == 4) {
    continue;
  }
  Console.WriteLine(i);
}
```

**[🔼Back to Top](#table-of-contents)**
