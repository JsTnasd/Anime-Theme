# Anime Theme

## Preview

### Wallpaper 1

![wallpaper 1](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper1.png)

### Wallpaper 2

![wallpaper 2](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper2.png)

### Wallpaper 3

![wallpaper 3](https://res.cloudinary.com/bfyniy76/image/upload/v1789947614/wallpaper3.png)

## Installation

1. Download `AnimeTheme.theme.css` from this repository.
2. Press `Win + R`.
3. Open `%appdata%\betterdiscord\themes`.
4. Move `AnimeTheme.theme.css` into that folder.
5. Open Discord and go to **Settings → Themes**.
6. Enable **Anime Theme**.

Only `AnimeTheme.theme.css` needs to be downloaded. It automatically imports the hosted `main.css` file.

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

`cover` fills the entire Discord window while maintaining the image's aspect ratio. Depending on the screen shape, a small part of the image may be cropped.


