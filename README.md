# joedockry.github.io

Angular built website hosted by github pages

Getting it up and running (method 2 in https://medium.com/tech-insights/how-to-deploy-angular-apps-to-github-pages-gh-pages-896c4e10f9b4):
1. Create a repo on github named joedockry.github.io
2. Clone the repo locally
3. Start an angular project from the cloned repo (`ng new appName --directory ./`)
4. Install Angular CLI gh-pages (`npm i angular-cli-ghpages`)
5. Build the angular app (`ng build --base-href https://joedockry.github.io/`)
6. Deploy to github pages (`npx angular-cli-ghpages -dir=dist/jdockry-portfolio`)