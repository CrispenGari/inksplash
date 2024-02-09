### inksplash

`inksplash` is a Python package that provides a versatile set of utilities for colorizing and styling text output in terminal environments.

### Table of Contents

- [inksplash](#inksplash)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Available styles and functions](#available-styles-and-functions)
  - [1. Basics](#1-basics)
  - [2. Text Styles](#2-text-styles)
  - [3. Bright Text Color Escape Codes](#3-bright-text-color-escape-codes)
  - [4. Background Color Escape Codes](#4-background-color-escape-codes)
- [Contributing](#contributing)
- [License](#license)

### Installation

You can install `inksplash` via pip:

```bash
pip install inksplash
```

### Usage

First, you need to import the `chameleon` module from the `inksplash` package:

```py
from inksplash import chameleon
print(chameleon.bg_bright_green(chameleon.italic(chameleon.black("Hello world"))))
```

<p align="center"><img src="/images/demo.jpg" alt="demo" with="300"/></p>

This example demonstrates how to use `chameleon` functions from `inksplash` to colorize and style text output. In this case, it applies a bright green background, italic style, and black text color to the string "Hello world".

### Features

- Easy-to-use API for applying various text styles and colors.
- Supports a wide range of styling options, including bold, italic, underline, foreground and background colors, etc.
- Compatible with ANSI terminal escape sequences, ensuring compatibility across different terminal emulators and platforms.

### Available styles and functions

The following are the functions that are available for text styles and colors.

#### 1. Basics

1. `blue`

   Applies a blue color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with blue color.

2. `green`

   Applies a green color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with green color.

3. `yellow`

   Applies a yellow color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with yellow color.

4. `white`

   Applies a white color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with white color.

5. `purple`

   Applies a purple color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with purple color.

6. `red`

   Applies a red color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with red color.

7. `cyan`

   Applies a cyan color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with cyan color.

8. `black`

   Applies a black color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with black color.

#### 2. Text Styles

1. `bold`

   Applies bold style to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bold style.

2. `underline`

   Applies underline style to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with underline style.

3. `italic`

   Applies italic style to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with italic style.

4. `strikethrough`

   Applies strikethrough style to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with strikethrough style.

#### 3. Bright Text Color Escape Codes

1. `bright_black`

   Applies a bright black color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright black color.

2. `bright_red`

   Applies a bright red color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright red color.

3. `bright_green`

   Applies a bright green color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright green color.

4. `bright_yellow`

   Applies a bright yellow color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright yellow color.

5. `bright_blue`

   Applies a bright blue color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright blue color.

6. `bright_purple`

   Applies a bright purple color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright purple color.

7. `bright_cyan`

   Applies a bright cyan color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright cyan color.

8. `bright_white`

   Applies a bright white color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with bright white color.

#### 4. Background Color Escape Codes

1. `bg_black`

   Applies a black background color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with black background color.

2. `bg_red`

   Applies a red background color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with red background color.

3. `bg_green`

   Applies a green background color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with green background color.

4. `bg_yellow`

   Applies a yellow background color to the text.

   **Parameters:**

   - `value` (str): The input text.

   **Returns:**

   - str: The input text with yellow background color.

5. `bg

### Contributing

Contributions to `inksplash` are welcome! Feel free to submit bug reports, feature requests, or pull requests on [GitHub](https://github.com/yourusername/inksplash).

### License

This project is licensed under the MIT License - see the [LICENSE](/LISENSE) file for details.
