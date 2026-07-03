# TNP Wire Prototype

A standalone prototype of **The National Press Wire's bookmarks + custom-folders feature** (item 3 from Jana's feedback).

This is a single self-contained `index.html` file using fictional mock data and in-memory state — nothing persists between page loads, and there is no backend.

## How to run

- Open `index.html` directly in a browser, or
- Visit the live GitHub Pages link: https://coby-anewai.github.io/tnp-wire-prototype/

## Not yet in this prototype

- **Item 1** — David's example stories (pending)
- **Item 2** — Story scorer (in progress)

## Known limitations

- No folder deletion yet — folders can be created and stories filed/unfiled, but there's no way to remove a folder itself.
- For a story that's only filed in a folder (not bookmarked), the wire-row ★ and the detail-sheet bookmark button can show different states, since they currently track "saved" slightly differently.
- "Add to folder" from the detail sheet may not visibly surface if a search term or folder/bookmark filter is currently hiding that story from the wire list.
