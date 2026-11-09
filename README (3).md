# AIMER Ambassador Program (website)

This repository holds the published website for https://referral.aimerbschool.com

- `index.html`: the whole web app
- `config.js`: connection details (the project address, the public key, and the final site address)
- `netlify.toml`: tells Netlify to publish these files and open every address in the app

Netlify settings: leave the build command empty. The publish directory is `.`.

The database, server functions, tests and backup tools are kept separately (the full project package). Nothing here is secret: the key in `config.js` is the public one.
