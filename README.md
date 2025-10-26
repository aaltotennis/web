# AT web

This is the source for AT website. It uses bun and 11ty, so what you need to do is:

1. `git clone` the repo in a folder of your choosing
2. install bun by following the instructions [here](https://bun.sh/docs/installation)
3. move in the `web` folder with `cd web`
4. install this project depenendencies by running `bun install`

After you've done all of the above, running a live preview of the website is as simple as:

```shell
bun start
```

Have fun hacking!

## Deployment

This website is automatically deployed to GitHub Pages using GitHub Actions. Every push to the `main` branch triggers a build and deployment to the `publish` branch, which is then served by GitHub Pages.

### Setup GitHub Pages (one-time)

To enable GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Navigate to **Pages** section (under "Code and automation")
3. Under "Build and deployment":
   - Source: Select **Deploy from a branch**
   - Branch: Select **publish** and **/ (root)** folder
4. Click **Save**

The site will be available at: https://aaltotennis.github.io/web/
