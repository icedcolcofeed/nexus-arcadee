# NEXUS ARCADE

A clean, responsive personal game hub for GitHub Pages.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `nexus-arcade`.
2. Upload `index.html` to the top level of the repository (not inside another folder).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait a minute or two. GitHub will show your website URL in the Pages section.

## Add games

- On the website, click **Upload** and choose a single `.html` or `.htm` game file.
- Those uploads are saved in that browser on that device using IndexedDB. They are not sent to GitHub and are not shared with other visitors.
- To publish a game for everyone: upload its game files into a folder in this repository, then edit `index.html` to add a game entry that links to that folder. The current upload control is a personal/local library, not a server-side upload service.

## Notes

- This starter version accepts single-file HTML games. Games that need separate images, audio, JavaScript, or CSS files should be uploaded to the repository with their full folder structure and linked from the site.
- Only upload games you own or have permission to distribute.
