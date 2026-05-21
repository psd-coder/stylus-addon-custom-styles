# Stylus custom styles

This repo is a collection of custom styles for websites, intended to be used with the Stylus browser extension.

Each stylesheet in this repo targets a specific site or UI tweak. Right now the repo includes a YouTube style, and more styles can be added over time.

## Files

- [YouTube style file](./youtube.css): makes the YouTube home feed cleaner and wider by adjusting the grid and hiding some sections such as Shorts.

## How to use with Stylus

1. Install the Stylus browser extension in your browser.
2. Open the site you want to customize.
3. Open the Stylus extension menu.
4. Create a new style for the current site.
5. Copy the contents of the matching stylesheet from this repo.
6. Paste the CSS into the Stylus editor.
7. Save the style.
8. Refresh the page.

## Example: YouTube

To use the current YouTube style:

1. Open `https://youtube.com`.
2. Create a new style in Stylus for `youtube.com`.
3. Copy the contents of [YouTube style file](./youtube.css).
4. Paste it into Stylus and save.

## Adding more styles

Add one CSS file per site or tweak. A simple naming pattern like `site-name.css` keeps the repo easy to scan.

## Updating a style

When a stylesheet changes in this repo, copy the updated contents into the corresponding style in Stylus and save again.

## Notes

- These styles are meant to be managed manually through Stylus.
- Site markup can change over time, so some selectors may need updates later.
