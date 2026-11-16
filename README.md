# NEXUS ARCADE — Public Game Library

## Publish the update
1. Download and extract this ZIP.
2. Open your GitHub repository named `nexus-arcade`.
3. Choose **Add file → Upload files**.
4. Upload `index.html` and `nexus_runner.html` from this folder. If GitHub asks whether to replace `index.html`, confirm the replacement.
5. Click **Commit changes**.
6. Wait a few minutes, then refresh your GitHub Pages website.

## Add another game so every visitor can play it
GitHub Pages is static hosting. A website cannot securely write new files into your GitHub repository just by using a browser upload button. To publish a new game for everyone:

1. Upload the game's `.html` file to the same repository folder as `index.html`.
2. Edit `index.html` on GitHub and add a card inside the `<section class="grid">` area. Example (change the name and file):

```html
<article class="game">
  <div class="emoji">🎮</div>
  <h3>My New Game</h3>
  <p>A short description of the game.</p>
  <a class="play" href="my-new-game.html" target="_blank" rel="noopener">PLAY NOW →</a>
</article>
```

3. Commit the change. After Pages redeploys, the new card appears for everyone.

The existing four mini-games are built into `index.html`; NEON DASH is included as `nexus_runner.html`.

**Note:** The `7245` entry screen is a casual front-end gate, not strong security. Anyone who can inspect the website files can discover or bypass it. Do not use it to protect private information.
