# Godot Editor Icons

A fast, searchable browser for the **editor icons of every stable Godot release** (1.0 – 4.7.2, 74 versions).
Pick a version, search, change the display size of all icons at once, open an icon to compare it at 16/24/32/48 px on a dark,
light or checkerboard background, and copy its name or the GDScript line that loads it.

* **Version selector** – each version shows only its own icons, with *NEW* and *GONE IN x* badges, filters for both, a list of icons removed since the previous release of the same major version. Only icons that are completely new or gone are marked; redesigns are deliberately not tracked.
* **Nothing is stored or sent** – no cookies, no local storage, no analytics, no external requests. The address (`#v=4.7&k=Node2D`) only carries the current version, search and opened icon so a link can point to it.

## Where the data comes from

The icons are read straight from Godot's git history (`editor/icons`, and `tools/editor/icons` for 1.x/2.x), one `*-stable` tag per version.

* `img/` – every distinct icon file once (the same icon in 40 versions is stored once),
* `data/<version>.json` – the icons of that version (name, file, size, first/last version, new in this version),
* `data/versions.json` – the version list.

Since/until/new are computed within one major version (3.0 renamed all icons, so a comparison across that border would mislead).

## License

* The icons are part of Godot Engine: (c) 2014-present Godot Engine contributors, (c) 2007-2014 Juan Linietsky, Ariel Manzur, **MIT (Expat) license** – see `LICENSE-GODOT-ICONS.txt`.
* The code of this site (everything else) is MIT licensed, see `LICENSE`.

This is an unofficial project, not affiliated with or endorsed by the Godot Foundation. "Godot" is a trademark of the Godot Foundation; the Godot logo is not used here.
