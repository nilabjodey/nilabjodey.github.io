# nilabjodey.github.io

Personal site of Nilabjo Dey: a split-flap message board that flips between sections, with a timetable-style details panel below.

One self-contained `index.html` (HTML, CSS and JS, no build step).

- Board messages: `MESSAGES` in the script (6 rows x 22 characters; `{R}{O}{Y}{G}{B}{V}{W}` are color tiles)
- Section details: the `<section class="pane">` blocks
- Contact form: posts to FormSubmit, which emails nilabjodey99@gmail.com

Preview locally: `python3 -m http.server` and open http://localhost:8000
