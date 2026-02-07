# Fonts Directory

## Genty Font Files

Place your Genty font files in this directory with the following naming convention:

- `Genty-Light.woff2` / `Genty-Light.woff` / `Genty-Light.ttf`
- `Genty-Regular.woff2` / `Genty-Regular.woff` / `Genty-Regular.ttf`
- `Genty-SemiBold.woff2` / `Genty-SemiBold.woff` / `Genty-SemiBold.ttf`
- `Genty-Bold.woff2` / `Genty-Bold.woff` / `Genty-Bold.ttf`

After adding the font files, uncomment the `@font-face` rules in `/css/fonts.css` to enable the custom Genty font.

## Font Formats

- **WOFF2**: Best compression, modern browsers
- **WOFF**: Fallback for older browsers
- **TTF**: Additional fallback if needed
