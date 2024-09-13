# WebFont Lato

Package for integrating `Lato` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/webfont-lato?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@bu0nq/webfont-lato?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/webfont-lato?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/webfont-lato
```

## Usage (CSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Lato', sans-serif;
}
```

### Importing

```css
@import "~@bu0nq/webfont-lato/css/all.css";
@import "~@bu0nq/webfont-lato/css/all-normal.css";
@import "~@bu0nq/webfont-lato/css/all-italic.css";
```

To import specific fonts, you can use:

```css
@import "~@bu0nq/webfont-lato/css/weight-100.css";
@import "~@bu0nq/webfont-lato/css/weight-100-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-100-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-200.css";
@import "~@bu0nq/webfont-lato/css/weight-200-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-200-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-300.css";
@import "~@bu0nq/webfont-lato/css/weight-300-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-300-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-400.css";
@import "~@bu0nq/webfont-lato/css/weight-400-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-400-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-500.css";
@import "~@bu0nq/webfont-lato/css/weight-500-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-500-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-600.css";
@import "~@bu0nq/webfont-lato/css/weight-600-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-600-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-700.css";
@import "~@bu0nq/webfont-lato/css/weight-700-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-700-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-800.css";
@import "~@bu0nq/webfont-lato/css/weight-800-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-800-italic.css";
@import "~@bu0nq/webfont-lato/css/weight-900.css";
@import "~@bu0nq/webfont-lato/css/weight-900-normal.css";
@import "~@bu0nq/webfont-lato/css/weight-900-italic.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following `CSS` variables to set the font display property with the default `swap` value if `CSS`
variables are not defined:

```css
:root {
  --font-display: swap;
  --font-display-lato: swap;
}
```

## Usage (LESS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Lato', sans-serif;
}
```

### Importing

```less
@import "~@bu0nq/webfont-lato/less/all";
@import "~@bu0nq/webfont-lato/less/all-normal";
@import "~@bu0nq/webfont-lato/less/all-italic";
```

To import specific fonts, you can use:

```less
@import "~@bu0nq/webfont-lato/less/_weight-100";
@import "~@bu0nq/webfont-lato/less/_weight-100-normal";
@import "~@bu0nq/webfont-lato/less/_weight-100-italic";
@import "~@bu0nq/webfont-lato/less/_weight-200";
@import "~@bu0nq/webfont-lato/less/_weight-200-normal";
@import "~@bu0nq/webfont-lato/less/_weight-200-italic";
@import "~@bu0nq/webfont-lato/less/_weight-300";
@import "~@bu0nq/webfont-lato/less/_weight-300-normal";
@import "~@bu0nq/webfont-lato/less/_weight-300-italic";
@import "~@bu0nq/webfont-lato/less/_weight-400";
@import "~@bu0nq/webfont-lato/less/_weight-400-normal";
@import "~@bu0nq/webfont-lato/less/_weight-400-italic";
@import "~@bu0nq/webfont-lato/less/_weight-500";
@import "~@bu0nq/webfont-lato/less/_weight-500-normal";
@import "~@bu0nq/webfont-lato/less/_weight-500-italic";
@import "~@bu0nq/webfont-lato/less/_weight-600";
@import "~@bu0nq/webfont-lato/less/_weight-600-normal";
@import "~@bu0nq/webfont-lato/less/_weight-600-italic";
@import "~@bu0nq/webfont-lato/less/_weight-700";
@import "~@bu0nq/webfont-lato/less/_weight-700-normal";
@import "~@bu0nq/webfont-lato/less/_weight-700-italic";
@import "~@bu0nq/webfont-lato/less/_weight-800";
@import "~@bu0nq/webfont-lato/less/_weight-800-normal";
@import "~@bu0nq/webfont-lato/less/_weight-800-italic";
@import "~@bu0nq/webfont-lato/less/_weight-900";
@import "~@bu0nq/webfont-lato/less/_weight-900-normal";
@import "~@bu0nq/webfont-lato/less/_weight-900-italic";
```

### Variables

Each font uses the following `LESS` variables to set the font display property with the default `swap` value if `LESS`
variables are not defined:

```less
@font-display: swap;
@font-display-lato: swap;
```

## Usage (SCSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Lato', sans-serif;
}
```

### Importing

```scss
@import "~@bu0nq/webfont-lato/scss/all";
@import "~@bu0nq/webfont-lato/scss/all-normal";
@import "~@bu0nq/webfont-lato/scss/all-italic";
```

To import specific fonts, you can use:

```scss
@import "~@bu0nq/webfont-lato/scss/weight-100";
@import "~@bu0nq/webfont-lato/scss/weight-100-normal";
@import "~@bu0nq/webfont-lato/scss/weight-100-italic";
@import "~@bu0nq/webfont-lato/scss/weight-200";
@import "~@bu0nq/webfont-lato/scss/weight-200-normal";
@import "~@bu0nq/webfont-lato/scss/weight-200-italic";
@import "~@bu0nq/webfont-lato/scss/weight-300";
@import "~@bu0nq/webfont-lato/scss/weight-300-normal";
@import "~@bu0nq/webfont-lato/scss/weight-300-italic";
@import "~@bu0nq/webfont-lato/scss/weight-400";
@import "~@bu0nq/webfont-lato/scss/weight-400-normal";
@import "~@bu0nq/webfont-lato/scss/weight-400-italic";
@import "~@bu0nq/webfont-lato/scss/weight-500";
@import "~@bu0nq/webfont-lato/scss/weight-500-normal";
@import "~@bu0nq/webfont-lato/scss/weight-500-italic";
@import "~@bu0nq/webfont-lato/scss/weight-600";
@import "~@bu0nq/webfont-lato/scss/weight-600-normal";
@import "~@bu0nq/webfont-lato/scss/weight-600-italic";
@import "~@bu0nq/webfont-lato/scss/weight-700";
@import "~@bu0nq/webfont-lato/scss/weight-700-normal";
@import "~@bu0nq/webfont-lato/scss/weight-700-italic";
@import "~@bu0nq/webfont-lato/scss/weight-800";
@import "~@bu0nq/webfont-lato/scss/weight-800-normal";
@import "~@bu0nq/webfont-lato/scss/weight-800-italic";
@import "~@bu0nq/webfont-lato/scss/weight-900";
@import "~@bu0nq/webfont-lato/scss/weight-900-normal";
@import "~@bu0nq/webfont-lato/scss/weight-900-italic";
```

### Variables

Each font uses the following `SCSS` variables to set the font display property with the default `swap` value if `SCSS`
variables are not defined:

```scss
$font-display: swap;
$font-display-lato: swap;
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.
