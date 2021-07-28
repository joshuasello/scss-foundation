# SCSS Foundation Module

This module provide some foundational resources such as mixins, helper classes and useful global variables.

## Installation

Clone this repository into your `scss` directory as `foundation`.

```bash
cd /<path-to-scss-directory>/
git clone https://github.com/joshuasello/scss-foundation.git foundation
```

## Setup

### Expected directory structure

```text
scss/
    foundation/
        ...
    home-page.scss
    ...  
```

## Importing

```scss
// File: home-page.scss

// Uses and such...

@import "foundation";

// The rest of your code...
```

## Predefined Globals

| Description             | Variable             | Default  |  
|-------------------------|----------------------|----------|
| Toggle debug styling    | `$debug-style-on`    | `false`  |
| Small size breakpoints  | `$small-breakpoint`  | `400px`  |
| Medium size breakpoints | `$medium-breakpoint` | `768px`  |
| Small size breakpoints  | `$large-breakpoint`  | `1024px` |

## Helpers

| Class Name     | Description                                  |
|----------------|----------------------------------------------|
|`.no-margin`    | Removes the margin from an element.          |
|`.hidden`       | Hides an element.                            |
|`.invisible`    | Hides visually but maintains layout          |
|`.display-block`| Display element as block                     |
|`.sr-only`      | Hidden with availability for screen readers. |
|`.clearfix`     | ...                                          |

## Mixins

| Mixin Usage                          | Description                                                              |
|--------------------------------------|--------------------------------------------------------------------------|
|`@include small-screen { ... }`       | Used to define a block of styles to use when the screen size is small.   |
|`@include medium-screen { ... }`      | Used to define a block of styles to use when the screen is medium sized. |
|`@include large-screen { ... }`       | Used to define a block of styles to use when the screen size is large.   |
|`@include prefers-dark-mode { ... }`  | Used to define a block of styles to use when light mode is preferred.    |
|`@include prefers-light-mode { ... }` | Used to define a block of styles to use when dark mode is preferred.     |

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Authors

- Joshua Sello (joshuasello@gmail.com)

## License

[MIT](https://choosealicense.com/licenses/mit/)
