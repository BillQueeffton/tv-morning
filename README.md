# tv-morning

The page behind the Morning app on the living-room TV. The app checks `index.html` here every 30 minutes and swaps it in if it changed.

- `index.html`: the TV page (surf, jump call, tide, weather, events, customise)
- `remote.html`: the iPhone remote (the TV serves its own copy on port 8765)

No calendar links, photos or personal data live here. Those stay on the TV in `config.json`.
