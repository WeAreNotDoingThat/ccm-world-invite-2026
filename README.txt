FASTEST HOSTING: NETLIFY DROP
1. Visit https://app.netlify.com/drop
2. Sign in or create a free Netlify account.
3. Drag the unzipped folder onto the page.
4. Share the public URL. Viewers need no account.

GITHUB PAGES
1. Create a public repository.
2. Upload index.html and locations.geojson.
3. Settings > Pages > Deploy from a branch.
4. Choose main and /root.
5. Share the generated github.io URL.

The map uses Leaflet 1.9.4 and OpenStreetMap tiles.
The GeoJSON is embedded inside index.html, so the hosted map works even if
locations.geojson is not separately loaded by the browser.
