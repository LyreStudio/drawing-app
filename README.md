# Drawing pad

A working drawing canvas with pen size, color, clear and PNG export. Drawings stay on this device and are not autosaved.

Adapted from [drawing-app in Brad Traversy's 50 Projects in 50 Days](https://github.com/bradtraversy/50projects50days/tree/c92b0bc3a87fc95d44b89552b7b6a2eeb36ca481/drawing-app), MIT, copyright 2022 Brad Traversy. The original [LICENSE](LICENSE) is retained. Lyre adaptations and server are MIT. [TEMPLATE.json](TEMPLATE.json) records exact upstream revision and per-file SHA-256.

## Run

Use Node 22 or newer, then `npm start` and open http://127.0.0.1:4173. No npm dependencies, account, API, remote font or internet access is needed for this app after download. `npm test` checks serving and private-file denial.

In Lyre use Add project → Clone repository with `https://github.com/LyreStudio/drawing-app.git`, or download a ZIP and add the extracted folder. A Lyre build containing this reviewed recipe also offers Marketplace → this app → Choose folder & install. Older installed releases need an app update for the new install recipe.

Edit index.html, style.css and script.js, then refresh the preview. New public files must be listed in public-files.json.

[Design](DESIGN.md) · [Agent guide](AGENTS.md) · [Validation](VALIDATION.md) · [Attribution](THIRD-PARTY.md)
