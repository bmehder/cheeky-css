# CheekyCSS

CheekyCSS is a lightweight functional CSS library designed to make styling your web projects fast and simple, with no build step required. It provides a set of utility classes that allow you to write clear, concise, and maintainable styles directly in your HTML.

## Installation

You can start using CheekyCSS in your project in two easy ways:

### 1. Link via GitHub Pages

Add the following `<link>` tag to the `<head>` of your HTML file to include CheekyCSS directly from GitHub Pages:

```html
<link rel="stylesheet" href="https://bradleymehder.github.io/cheekycss/cheeky.css" />
```

### 2. Copy the CSS file (recommended)

Alternatively, download the `cheeky.css` file from the repository and include it locally in your project:

```html
<link rel="stylesheet" href="path/to/cheeky.css" />
```

## Example Usage

Here is a simple example demonstrating how to use CheekyCSS utility classes in your HTML:

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CheekyCSS Example</title>
  <link rel="stylesheet" href="https://bmehder.github.io/cheeky-css/cheeky.css" />
</head>

<body class="p-4 text-center">
  <h1 class="mb-4">Welcome to CheekyCSS</h1>

  <div class="flex justify-content-center flex-wrap gap-2 mb-4 text-center">
    <div class="p-3">Box 1</div>
    <div class="p-3">Box 2</div>
    <div class="p-3">Box 3</div>
  </div>

  <p class="italic">Simple, clean, and easy to use.</p>
</body>

</html>
```

## Key Features

- **Utility Classes:** A growing set of utility classes for margins, padding, basic typography, layout, positioning, and more.
- **Logical Properties:** Uses CSS logical properties for better internationalization and flexible layouts.
- **No Build Step:** Just include the CSS file — no preprocessing or bundling required.
- **Tiny File Size:** Minimal footprint to keep your projects fast and lightweight.

## Alternate Class Names

CheekyCSS provides both verbose and concise aliases for utility classes. For example, you can use the verbose `.margin-block-1` or the concise alias `.mb-1` to apply the same margin. This flexibility allows you to choose the style that best fits your project and coding preferences.

## Philosophy

CheekyCSS is built with clarity and simplicity in mind. It offers concise aliases for common CSS properties to speed up development without sacrificing readability. The goal is to empower developers to write clean, maintainable markup with minimal overhead.

## License

This project is licensed under the MIT License.  
See [https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT) for details.
