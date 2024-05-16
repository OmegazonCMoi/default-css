# Default.css File

A Default CSS File to avoid re-creating the same variables multiple times for different projects.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

`default-css` is a standardized CSS file that contains commonly used CSS variables and styles. This file is designed to be a starting point for new projects, saving time by reducing the need to recreate the same variables and styles across different projects.

## Features

- Predefined CSS variables for colors, fonts, and spacing.
- Basic styles for typography, buttons, and forms.
- Responsive design utilities.
- Easy to integrate into any project.

## Installation

You can add `default-css` to your project by downloading the CSS file or by using a CDN link.

### Download

1. Download the `default.css` file from the repository.
2. Place the file in your project's CSS directory.

### CDN

Add the following link to your HTML file within the `<head>` section:

```html
<link rel="stylesheet" href="path/default.css">
```

## Usage

To use the predefined variables and styles, simply include the `default.css` file in your project and start using the variables in your CSS.

### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <link rel="stylesheet" href="path/to/default.css">
</head>
<body>
    <h1>Hello, World!</h1>
    <button class="w30 center pad-t5">Click Me</button>
<!-- w30 for width: 30;
     center to center the button
     pad-t5 for padding-top: 5%;-->
</body>
</html>
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please create an issue or submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch with your feature or fix.
3. Commit your changes.
4. Push the branch to your fork.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg) ![forthebadge](https://forthebadge.com/images/badges/open-source.svg) ![forthebadge](https://forthebadge.com/images/badges/made-with-css.svg)
