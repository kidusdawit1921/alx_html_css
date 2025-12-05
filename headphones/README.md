# Project README

## Overview

This project is a responsive web page built from a provided Figma design. It includes both desktop and mobile layouts, interactive elements, and a max content width of 1000px. If you are developing locally or contributing to this repository, please read the full instructions below.

## Figma Access

To fully explore spacing, components, and interactions, **duplicate the Figma file to your drafts**.

### Fonts

If your system does not have the fonts used in the design, download and install:

* **Source Sans Pro**
* **Spin Cycle OT**

These fonts are required to match the Figma design precisely.

## Responsive Behavior

The site must adapt to different screen sizes according to the following rules:

* At **480px or below**, the layout switches to the mobile version.
* Content has a **maximum width of 1000px**, centered on the page.

## Interactions

Follow these design interaction requirements:

* **Links hover/active state:** `#FF6565`
* **Button hover/active state:** `opacity: 0.9`

## Development Notes

* Some design values in Figma may appear as floating‑point numbers. You can safely round them.
* Ensure responsiveness is tested on real devices or emulators.
* Match spacing, typography, and alignment as closely as possible to the Figma design.

## Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Install dependencies (if applicable):

   ```bash
   npm install
   ```
3. Start the development server:

   ```bash
   npm run dev
   ```
4. Open the project in your browser at the URL printed in your terminal.

## Folder Structure

```
project-root/
├── assets/
├── css/
├── js/
├── index.html
└── README.md
```

## Contributing

Pull requests are welcome! Ensure code style is consistent and changes reflect the Figma design.

## License

This project is provided for learning and development purposes. Add your license information here if necessary.
