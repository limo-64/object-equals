# Object Equals Utility 🔍

![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-brightgreen) ![Releases](https://img.shields.io/badge/Releases-latest-blue)

Welcome to the **Object Equals** repository! This utility provides a fast, flexible, and robust solution for deep equality comparison. It features type-specific logic and an engine-aware design to meet your needs.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

In modern applications, comparing objects can be complex. The **Object Equals** utility simplifies this process by providing a reliable way to check for deep equality. Whether you're working with nested objects or arrays, this utility handles various data types with ease.

You can find the latest releases of the utility [here](https://github.com/limo-64/object-equals/releases). Download the appropriate file and execute it to get started.

## Features

- **Fast Performance**: Optimized for speed, this utility minimizes processing time during comparisons.
- **Flexible Logic**: Supports various data types, including objects, arrays, and primitives.
- **Robust Design**: Built to handle edge cases and avoid common pitfalls in equality checks.
- **Type-Specific Handling**: Tailors comparison logic based on the type of data being evaluated.
- **Engine Awareness**: Adapts to different JavaScript engines for improved compatibility.

## Installation

To install the **Object Equals** utility, you can clone the repository or download the release files directly. Here’s how to do it:

### Cloning the Repository

```bash
git clone https://github.com/limo-64/object-equals.git
cd object-equals
npm install
```

### Downloading the Release

Visit the [Releases](https://github.com/limo-64/object-equals/releases) section to download the latest version. Execute the file according to your environment.

## Usage

Using the **Object Equals** utility is straightforward. Below is a basic example to illustrate how to perform deep equality checks.

### Basic Example

```javascript
const objectEquals = require('object-equals');

const obj1 = { a: 1, b: { c: 2 } };
const obj2 = { a: 1, b: { c: 2 } };

const result = objectEquals(obj1, obj2);
console.log(result); // true
```

### Handling Different Types

The utility can compare various types, including arrays and nested objects.

```javascript
const arr1 = [1, 2, { a: 3 }];
const arr2 = [1, 2, { a: 3 }];

const result = objectEquals(arr1, arr2);
console.log(result); // true
```

## Examples

Here are some more detailed examples to help you understand how to use the utility effectively.

### Comparing Nested Objects

```javascript
const objA = { x: { y: 10, z: 20 } };
const objB = { x: { y: 10, z: 20 } };

console.log(objectEquals(objA, objB)); // true
```

### Comparing Arrays

```javascript
const array1 = [1, 2, 3];
const array2 = [1, 2, 3];

console.log(objectEquals(array1, array2)); // true
```

### Edge Cases

The utility also handles edge cases gracefully.

```javascript
const objC = { a: undefined };
const objD = { a: null };

console.log(objectEquals(objC, objD)); // false
```

## Contributing

We welcome contributions to the **Object Equals** utility! If you have suggestions, bug fixes, or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please reach out to the repository maintainers. You can find their contact information in the repository settings.

For the latest updates and releases, visit the [Releases](https://github.com/limo-64/object-equals/releases) section. Download the latest version and execute it to start using the **Object Equals** utility.

---

Thank you for checking out the **Object Equals** utility! We hope it serves your needs for deep equality comparisons effectively.