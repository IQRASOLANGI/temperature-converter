# Temperature Converter

A responsive, dependency-free web tool that converts temperatures between **Celsius**, **Fahrenheit** and **Kelvin**, with real-time input validation and physical-limit checks.

## Features

- Choose both the input unit and the target unit, then convert with one click (includes a swap button)
- Strict numeric validation with clear, inline error messages
- Absolute-zero protection (values below −273.15 °C / −459.67 °F / 0 K are rejected)
- Context label for the result (freezing, mild, hot, boiling and so on)
- Keyboard friendly (Enter to convert), accessible markup with ARIA live regions
- Responsive layout with automatic light and dark themes

## Tech Stack

HTML5 · CSS3 (custom properties, Flexbox, Grid) · Vanilla JavaScript (ES6)

## Run Locally

No build step required. Open `index.html` in any modern browser.

## Project Structure

```
├── index.html   # Markup, styles and logic in one self-contained file
└── README.md
```

## Conversion Formulas

| From | To Celsius | To Fahrenheit | To Kelvin |
|------|------------|---------------|-----------|
| Celsius | — | °C × 9/5 + 32 | °C + 273.15 |
| Fahrenheit | (°F − 32) × 5/9 | — | (°F − 32) × 5/9 + 273.15 |
| Kelvin | K − 273.15 | (K − 273.15) × 9/5 + 32 | — |
