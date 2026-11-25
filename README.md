# Campus Favorites

A small React app to browse students and add/remove favourites.

## Run locally
1. Install [Node.js](https://nodejs.org/).
2. Open this project folder in VS Code or a terminal.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL shown in the terminal.

## Build check
Run `npm run build`. The production-ready site is generated in the `dist` folder.

## Deploy (easy option: Vercel)
1. Push this project to a GitHub repository.
2. Sign in to [Vercel](https://vercel.com/) using GitHub.
3. Select **Add New → Project** and import the repository.
4. Keep the defaults (Vite is detected automatically): Build command `npm run build`, Output directory `dist`.
5. Click **Deploy**. Vercel will give you a live website URL and automatically redeploy after future GitHub pushes.

The included `vercel.json` handles page routes so links work after deployment.
