# Noir Glass

A monochrome glass theme for Discord with transparent panels, smooth animations and three selectable wallpapers.

## Preview

### Wallpaper 1

![Noir Glass with wallpaper 1](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper1.png)

### Wallpaper 2

![Noir Glass with wallpaper 2](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper2.png)

### Wallpaper 3

![Noir Glass with wallpaper 3](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper3.png)

## Features

- Monochrome black-and-white appearance
- Transparent glass-style panels
- Three included wallpapers
- Responsive wallpaper scaling for different screen sizes
- Improved channel, mention and server visibility
- Smooth message, popout, button and server animations
- Reduced-motion support

## Installation

1. Download `Anime-theme.css` from this repository.
2. Move it into your Discord client's themes folder.
3. Open your client's theme settings.
4. Enable **Noir Glass**.

The theme file imports `main.css` automatically, so both files must remain available in this repository.

## Selecting a Wallpaper

Open `Anime-theme.css` and find this line inside `:root`:

```css
--background-image: var(--wallpaper-1);
```

Change only the final number:

```css
/* Wallpaper 1 */
--background-image: var(--wallpaper-1);

/* Wallpaper 2 */
--background-image: var(--wallpaper-2);

/* Wallpaper 3 */
--background-image: var(--wallpaper-3);
```

Only one `--background-image` line should be active at a time.

## Adding a Custom Wallpaper

You can add another wallpaper by following the same format. For example, add `--wallpaper-4` alongside the existing wallpaper variables:

```css
:root {
  --wallpaper-1: url("YOUR_FIRST_WALLPAPER_URL");
  --wallpaper-2: url("YOUR_SECOND_WALLPAPER_URL");
  --wallpaper-3: url("YOUR_THIRD_WALLPAPER_URL");
  --wallpaper-4: url("YOUR_CUSTOM_WALLPAPER_URL");

  --background-image: var(--wallpaper-4);
}
```

Replace `YOUR_CUSTOM_WALLPAPER_URL` with a direct image URL. The URL should point directly to an image such as a `.png`, `.jpg`, `.jpeg` or `.webp` file.

## Wallpaper Scaling

The wallpaper automatically adapts to the user's window and screen size with these settings:

```css
--background-position: center center;
--background-size: cover;
--background-attachment: fixed;
```

`cover` fills the entire Discord window while maintaining the image's aspect ratio. Depending on the screen shape, a small part of the image may be cropped.

## Repository Files

- `Anime-theme.css` — theme metadata, wallpapers, colors and personal customization
- `main.css` — core interface styles and animations
- `README.md` — installation and customization instructions
- `LICENSE` — project and third-party licensing information

## Updating

Changes made to the hosted `main.css` are loaded automatically by the theme. If an update does not appear immediately, reload Discord with `Ctrl + R` or restart the client.

## License

This project contains modified portions of ClearVision v7 licensed under Apache-2.0. Keep the required copyright and license notices when redistributing modified versions.


