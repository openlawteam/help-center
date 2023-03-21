# Help Center

Markdown files for rendering pages in a Tribute DAO dApp's Help Center.

## Accessing files

```
GET https://cdn.jsdelivr.net/gh/openlawteam/help-center/{filename}
```

## What should each file contain?

Just the body content of the page. The title will be set via configuration which lives elsewhere (i.e. a Mongo document)

## Adding a file for immediate publishing

1. From this repository click ["Add File"](https://github.com/openlawteam/help-center/new/main)
2. Type in a short, lowercased, dash-separated ("kebab case") filename at the top (e.g. `meetups.md`)
3. Type the page's content in [Markdown](https://www.markdownguide.org/cheat-sheet) format
4. Once ready, click "Commit changes..." at the top-right of the editor
5. **Optional:** Add any special commit notes you may have, otherwise leave defaults
6. Leave "Commit directly to the main branch" selected
7. Click "Commit changes"

## Drafting a file for publishing later

1. Follow steps 1-5 above
2. Select "Create a new branch for this commit and start a pull request"
3. Click "Propose changes"
6. Click the green button to create the pull request
7. Once your draft is ready, merge the pull request into the `main` branch
