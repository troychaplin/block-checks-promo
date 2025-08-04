# Block Checks Promo

A promotional WordPress block theme designed to showcase the Block Accessibility Checks plugin, currently in early stages of development.

## Overview

Block Checks Promo is a custom WordPress block theme specifically created to demonstrate and promote the Block Accessibility Checks plugin. The theme features a clean, minimal design using a carefully curated dual-color palette with white, and serves as both a functional theme and a showcase for accessibility-focused block development. Built using the latest WordPress block editor (Gutenberg) capabilities, this theme leverages modern web standards and accessibility best practices.

## Development Status

🚧 **Early Development** - This promotional theme is currently in active development and not ready for production use. It's being developed alongside the Block Accessibility Checks plugin to showcase accessibility features and best practices.

## Purpose

This theme serves multiple purposes:
- **Plugin Promotion**: Showcases the capabilities of the Block Accessibility Checks plugin
- **Accessibility Demo**: Demonstrates proper implementation of accessibility checks in blocks
- **Development Testing**: Provides a testing environment for plugin functionality
- **Educational Resource**: Shows best practices for accessible block theme development

## Color System

Color scheme has been generated using the [Tailwind Colour Generator](https://uicolors.app/) with color pairings selected from randomly generated palettes via [Coolors](https://coolors.co/).

### Color Palette Structure

Each color variation follows a consistent naming convention with Tailwind generator references:

| Colour Palette Name  | Tailwind Generator Reference |
|----------------------|------------------------------|
| Color Name: Faint    | 50                           |
| Color Name: Pale     | 100                          |
| Color Name: Light    | 200                          |
| Color Name: Regular  | 400                          |
| Color Name: Medium   | 600                          |
| Color Name: Headings | 800                          |
| Color Name: Text     | 950                          |

### Available Style Variations

#### Default
- Brown: `#865f4b` — [Roman Coffee](https://uicolors.app/generate/865f4b)
- Blue: `#456990` — [Kashmir Blue](https://uicolors.app/generate/456990)
- Green: `#19231A` — [Hunter Green](https://uicolors.app/generate/19231A)

## Theme Structure

```
block-checks-promo/
├── README.md
├── style.css
├── theme.json          # Theme configuration and global styles
├── assets/
│   └── fonts/          # Custom font files (Inter, Space Grotesk)
│       ├── inter/
│       └── space-grotesk/
├── parts/              # Template parts
│   ├── footer.html
│   └── header.html
└── templates/          # Block templates
    ├── archive.html
    ├── index.html
    └── page.html
```

## Requirements

- WordPress 6.0 or higher
- PHP 8.0 or higher
- Block editor (Gutenberg) enabled
- Block Accessibility Checks plugin (recommended for full functionality)

## Related Projects

This theme is part of the Block Accessibility Checks ecosystem:
- **[Block Accessibility Checks Plugin](../../../plugins/block-accessibility-checks/)** - The main accessibility plugin
- **[Block Check Integration Example](../../../plugins/block-check-integration-example/)** - Example plugin showing integration patterns

## Author

**Troy Chaplin**
- Website: [troychaplin.ca](https://troychaplin.ca)
- GitHub: [@troychaplin](https://github.com/troychaplin)

## License

This theme is licensed under the GPL v2 or later.

---

*Last updated: August 2025*