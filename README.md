# zro_soon: Coming Soon page with a dotted world map

A single-file "coming soon" page. No build step, no dependencies.

- A dot-grid logo that flies in from scattered dots when the page loads
- A dotted world map that spreads out, holds, melts away and returns from a new starting point
- Location tags that flicker like a status display
- Mouse / touch pointer pushes the dots away and tints them purple; while the map is hidden the pointer lights it up locally

## Use it

Open `index.html` in a browser, or upload it as the home page of any domain.

## Customise

All settings are at the top of the `<script>` in `index.html`:

- `LOGO`: the dot grid of the logo (`n` = dark dot, `b` = second colour, `.` = empty). Replace it with your own logo.
- `PLACES`: the cities that get a coordinate tag.
- `SPREAD`, `HOLD`, `MELT`, `GAP`: timing of the map cycle, in seconds.
- Text: "Coming soon" and "Hosted by ..." are plain HTML at the bottom of `<body>`.

## Credits

World land outline: [Natural Earth](https://www.naturalearthdata.com/) 1:110m land (public domain).
