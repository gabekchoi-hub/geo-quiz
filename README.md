# Geography Quiz

A single-page quiz for learning where US states and world countries are.

**To play:** open `geo-quiz.html` in a browser. It needs an internet connection to download the map data.

## Maps
- **US States:** all 50.
- **World Countries:** the 193 UN member states, with an optional region filter (Africa, Asia, Europe, North & Central America, South America, Oceania).

## Modes
- **Find it:** you're given a name, and you click it on the map.
- **Name it:** a state or country is highlighted, and you type its name. Close misspellings and common alternate names (UK, Ivory Coast, Czech Republic…) are accepted.

After 5 wrong tries the answer is shown. Correct answers fill **green** and misses fill **red**.

## Features
- Missed ones go on a practice list. Use **Practice missed** to drill them, or **Reset missed list** to clear it.
- Progress saves automatically in your browser, separately for each map, mode and region.
- Hovering over a small state or country opens a magnifier.
- The world map can be zoomed and panned. Tiny countries get a clickable dot.
- Keyboard play in Find it mode: the arrow keys move between neighbors, Enter picks, and Esc clears.

Map data: [us-atlas](https://github.com/topojson/us-atlas) and [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth), drawn with [D3](https://d3js.org/).
