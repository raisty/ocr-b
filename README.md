# Machine Monospace Font

Machine is a monospace font originally developed in 1968 by Adrian Frutiger as an OCR font. This distribution brings many improvements, including extended Latin character support for Eastern European languages.

## Font Information

The font follows the [Google Fonts specification](https://github.com/googlefonts/gf-docs) and includes:

- `DESCRIPTION.en_us.html` - Font description and details
- `FONTLOG.txt` - Detailed font history and acknowledgments
- `machine.css` - CSS for web usage
- `Machine-Regular.ttf` - TrueType font file
- `METADATA.pb` - Font metadata for Google Fonts
- `OFL.txt` - SIL Open Font License v1.1

## Development

The font source is in TTF format, which can be opened and modified using:

- [Glyphs](https://glyphsapp.com)
- [FontForge](https://fontforge.org)
- [FontLab](https://fontlab.com)
- any other font editor that supports TTF format

To modify the font:

1. Install font editor
2. Open the `Machine-Regular.ttf` file
3. Make your changes and export the font files

## Usage

### Importing the font

```css
@font-face {
  font-family: "machine";
  src: url(Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

### CDN

CSS import of the latest version

```css
@font-face {
  font-family: "machine";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/machine/Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

CSS with Minor updates and patch fixes within a major version

```css
@font-face {
  font-family: "machine";
  src: url(https://cdn.jsdelivr.net/gh/rastislavcore/machine@1/Machine-Regular.ttf) format("truetype");
  font-display: swap;
}
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1. See the [OFL.txt](OFL.txt) file for full details.

## Funding

If you find this project useful, please consider supporting it:

- [GitHub Sponsors](https://github.com/sponsors/rastislavcore)

List of sponsors: [![GitHub Sponsors](https://img.shields.io/github/sponsors/rastislavcore?label=Sponsors&logo=githubsponsors&color=EA4AAA)](https://github.com/sponsors/rastislavcore)
