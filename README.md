# simple-webpage-boilerplate

Developing environment for simple static webpage with github pages.

## Developing

```
yarn
yarn start
```

Start a local server at `localhost:4000`.

Edit `public/index.html` `index.babel` `index.styl`.

## Deployment

Edit `circle.yml` and fill in `GIT_REPO` field.

Open [circleci](https://circleci.com) and build project.

Project Settings -> Checkout SSH Keys -> Add user key

Then, rebuild.
