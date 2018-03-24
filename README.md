# better-website

Github pages hosted react application intended to be used as my website.

## steps taken to setup and deploy
1. `$ pnpx create-react-app better-website`
2. `$ cd better-website`
3. `$ pnpm install gh-pages --save-dev`
4. Added package.json property `"homepage": "http://omalleya.github.io/better-website"`
- omalleya.github.io is redirected to aidanomalley.com
5. Added package.json scripts:
- `"predeploy": "npm run build",`
- `"deploy": "gh-pages -d build"`
6. Connected the project with git repository matching the homepage property set in step 4.
7. `$ pnpm run deploy`
