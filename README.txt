Local preview (personal-site usage)

Recommended (Node-based workflow)
1. Clone this repository and move into its root directory.
2. Install dependencies once:

   npm install

3. Start the bundled dev server (Vite-style port 4173):

   npm run dev

4. Visit the printed URL (defaults to http://localhost:4173). Use Ctrl+C to stop the server.

Fallback options (pick one when Node/npm are unavailable)

   - Global serve install:
     npm install --global serve
     serve .

   - Python http.server (4000 shown, pick any open port):
     python3 -m http.server 4000

Tips:
- The site is static, so no build step is required beyond Sass-to-CSS compilation if you edit `assets/sass`.
- `npm run dev` uses the local `serve` dependency, so no global npm installs are necessary.