# Blue Prince Notebook

A small mobile web app for keeping notes per room while playing Blue Prince. Open a room by typing its exact name, then keep track of what to do, what you found and what you noticed there.

## Features

- Open a room or place (like the grounds or underground areas) by its exact in-game name, without a list of names (no spoilers)
- Each room page uses the room's colour, number and a drawing of its standard door layout
- Per room: to-dos (checklist), found items and notes
- To-dos and finds are either "always" or tied to a specific day
- Notes always carry a day stamp and can be edited
- Current day in the header, with quick − / + buttons and a way back to today after looking at earlier days
- To-dos page with tabs for today, always and past days, plus search and colour filters
- Past days: per item or in bulk, make it "always" or delete it
- Rooms page with search, colour filters and sorting
- A sealed hint per room, opened only after confirming, with a deeper second hint once the first is open
- Mark a room as upgraded, optionally with its new name or a short note, shown on the room and in the room list
- Secret rooms get a stop-sign style label; when the room that unlocks them is not in your notebook yet (not named, to avoid spoilers), the page stays folded until you confirm
- Delete a room including all its notes

## Usage

Open `index.html` in a browser, or host it on GitHub Pages. On a phone, add it to your home screen for an app-like experience.

## Data

Everything is stored in the browser's local storage on the device you use. Notes do not sync between devices, and clearing site data removes them.

## Hosting on GitHub Pages

1. Push `index.html` and `README.md` to the `main` branch
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch", branch `main`, folder `/ (root)`
4. The app is available at `https://<username>.github.io/blue-prince-notebook/`

## Disclaimer

A fan-made notebook, not affiliated with the makers of Blue Prince. Hints are based on the community wiki at blueprince.wiki.gg and may be incomplete.
