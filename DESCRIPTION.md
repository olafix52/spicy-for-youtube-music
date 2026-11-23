Brings the look, spring physics, and layout of [Spicy Lyrics](https://github.com/Spikerko/spicy-lyrics) to YouTube Music.

## Features

- **Word bounce & letter wave:** Syllables rise and settle on Spicy's spring curves, while held syllables swell and glow letter by letter.
- **Distance blur & hover box:** Distant lines blur and dim progressively, with a soft hover highlight box behind the pointer, instrumental progress dots, and dimmed background vocals/romanization.
- **Spicy fullscreen & Canvas Immersive:** Classic centered cover with hover controls, full-height animated cover stage with bottom-left dock when Better Lyrics Shaders provides an animated cover, and a compact portrait layout.
- **Popup Lyrics (PiP):** Matching blurred backdrop, rounded cover with hover controls, glass progress bar, and spring-animated lyrics.
- **Refined YouTube Music UI:** Liquid Glass styling across the side-panel tab bar, Queue and Related tabs, video player frame, dock controls, and browse/home pages, with bundled SF Pro & international SF fonts (Arabic, Hebrew, Armenian, Georgian).

## Recommended

- **[Better Lyrics Shaders](https://github.com/better-lyrics/shaders):** Includes a tuned Kawarp preset (`shader.json`) matching Spicy Lyrics 6.5.0. Falls back to a blurred CSS cover background when Shaders is not installed.
- **Local SF Pro fonts (optional):** Loaded via `fonts.css` with Inter fallback when offline.

## Tuning

Edit the **Tunables** block at the top of `style.css` to adjust:

- `$spicy-glass-style` (`liquid` default, `frosted`, or `lite` with no backdrop blur) and `$spicy-scroll-fade` (`false` default, or `true`);
- lyrics scale (`--spicy-lyrics-scale`), line gap (`--spicy-line-gap`), distance blur, line opacities, word bounce, cover size, and hover box.
