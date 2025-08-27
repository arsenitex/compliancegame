# Custom Fonts

This directory should contain the custom font files:

## Required Font Files:
- `ESKlarheitKurrent.woff2` (ES Klarheit Kurrent font in WOFF2 format)
- `ESKlarheitKurrent.woff` (ES Klarheit Kurrent font in WOFF format)
- `JoganSoft.woff2` (Jogan Soft font in WOFF2 format)
- `JoganSoft.woff` (Jogan Soft font in WOFF format)

## Usage:
- **ES Klarheit Kurrent**: Used for headings, titles, and important UI elements
- **Jogan Soft**: Used as the main body font throughout the application

## Fallbacks:
The CSS includes fallbacks to ensure the game works even without the custom fonts:
- ES Klarheit Kurrent falls back to Orbitron (Google Fonts)
- Jogan Soft falls back to Exo 2 (Google Fonts)

## Note:
If the font files are not available, the game will automatically use the fallback fonts and still function properly.