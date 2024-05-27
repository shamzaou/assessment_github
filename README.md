# ft_printf // Effective Use of Git && Github

## Overview

`ft_printf` is a project from the 42 School curriculum designed to replicate the functionality of the standard `printf` function in C. This project aims to deepen understanding of variadic functions, formatted output, and overall C programming.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [Development](#development)
- [Contributing](#contributing)
- [Contact](#contact)

## Project Description

The `ft_printf` function is a variadic function that mimics the behavior of the standard `printf` function in C. It supports a variety of format specifiers and provides formatted output for strings, characters, integers, and more.

## Features

- Supports the following format specifiers:
  - `%c` - Character
  - `%s` - String
  - `%p` - Pointer
  - `%d` - Decimal integer
  - `%i` - Integer
  - `%u` - Unsigned integer
  - `%x` - Hexadecimal (lowercase)
  - `%X` - Hexadecimal (uppercase)
  - `%%` - Percent sign

## Usage

To use `ft_printf`, include the header file in your C program and link the library during compilation.

```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    return 0;
}
```
## Installation

1. Clone the repository:

```
git clone https://github.com/shamzaou/ft_printf_github_assessment.git
```

2. Navigate to the project directory:

```
cd ft_printf_github_assessment
```

3. Compile the library:

```
make
```

4. Include the ft_printf.h header in your project and link the compiled library.

## Development

### Repository Setup
This repository follows best practices for Git and GitHub. The key elements include:

  - **Clear and concise commit messages:** Commit messages should be meaningful and describe the changes made.
  - **Feature branches:** Use separate branches for new features and bug fixes.
  - **Pull requests:** All changes are reviewed through pull requests to ensure code quality.
  - **Issue tracking:** Use GitHub issues to track bugs and feature requests.

### Git Workflow

Create a new branch for your feature or bug fix:

    git checkout -b feature-name

Make your changes and commit them with descriptive messages:

    git commit -m "Add feature description"

Push your branch to the remote repository:

    git push origin feature-name

Open a pull request on GitHub and request a review.

## Contributing

Contributions are welcome! Please follow the guidelines below to ensure smooth collaboration:

  - Fork the repository.
  - Create a new branch for your changes.
  - Ensure your code follows the project's coding standards.
  - Write clear and concise commit messages.
  - Submit a pull request with a detailed description of your changes.

## Contact
For any questions or feedback, please open an issue on GitHub or contact me at salim.hamzaoui.pro@outlook.com .
