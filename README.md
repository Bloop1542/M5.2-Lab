# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```
## Accessibility Lab Answers

    Semantic HTML

        Replaced <font> tags with proper headings (<h1>-<h3>)

        Used <nav>, <article>, <aside> for structure

        Added ARIA roles/labels (e.g., aria-label="Main navigation")

    Color Contrast

        Changed background/text colors to meet standards

    Keyboard Navigation

        Made all interactive elements (links/buttons) keyboard-focusable

        Added visible focus indicators (:focus styles)

    Image Accessibility

        Added descriptive alt text for all images

    Table Improvements

        Added <caption> and scope="col" attributes

        Proper header/data cell relationships

    Form Accessibility

        Added hidden labels for search input

        Associated labels with inputs using for/id

        Converted comment toggle to a <button>

    Audio Accessibility

        Added transcript link for hearing-impaired users

        Included fallback download link

    Responsive Design

        Added mobile-friendly layout (CSS Grid/Flexbox)

        Improved text readability with proper spacing

    ARIA Enhancements

        aria-live="polite" for dynamic comments

        aria-expanded for show/hide state

    Content Structure

        Logical heading hierarchy

        Clear content grouping with <section>

        Semantic list structures