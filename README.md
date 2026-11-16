# UnitoEat · GitHub Pages release v1.0.0

A standalone interactive version of the HKUST UnitoEat student project. The ZIP contains the finished site: no installation or build step is needed.

## Publish on GitHub Pages

1. Extract the ZIP.
2. Create a GitHub repository, for example `unitoeat`. Upload the extracted contents to the root of its `main` branch. Keep `index.html`, `.nojekyll`, the CSS/JS files and `sample/` at their original relative paths. Do not upload the ZIP itself or wrap the files in an additional folder. Some file browsers hide `.nojekyll`; use your file browser's show-hidden-files option or Git to include it.
3. In the repository, go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then **main → /(root) → Save**.
4. Open the URL shown in Pages settings after deployment. Use that URL for your presentation QR code.

See [GitHub's publishing guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Preview and record

Open `index.html` after extracting. For reliable local storage across refreshes, use GitHub Pages or, from the extracted directory, run `python3 -m http.server 8000` and open `http://localhost:8000/`.

- Open **Demo profiles → Ada Chan**.
- Open the JoA special, choose a meal and pickup slot, and complete the simulated checkout. JoA already has one starter reservation, so Ada brings it to the two-portion minimum.
- Click Ada's name and **Sign out**. Open **Demo profiles → JoA** and select **Confirm batch early**.
- To repeat the sequence, open **Demo profiles → Demo administrator → Reset sample data**. This restores the initial sample listings, orders, ideas and comments. It leaves locally created profiles and independent listings in place.

Photos, profiles, reservations, comments, votes and merchant changes are stored in the current browser. They are not shared with other visitors or with the original hosted site. Profile switching is a demo interaction, not authentication. No payment or account credentials are collected. The listed dishes are fictional examples and no food is ordered.
