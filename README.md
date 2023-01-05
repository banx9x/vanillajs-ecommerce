# VanillaJS Ecommerce Project

## Deployment

Push the code to Github then link the repo to a Vercel or Netlify project for automatic deployment on push or pull request, or manually deploy following the instructions below

### Vercel

- Install `vercel` global

  ```sh
  npm i -g vercel
  ```

- Deploy

  ```sh
  vercel .
  ```

  Then follow the instructions

### Netlify

- Install `netlify-cli` global

  ```sh
  npm i -g netlify-cli
  ```

- Init project (Login require)

  ```sh
  ntl init
  ```

- Build project
  
  ```sh
  npm run build
  ```

- Deploy

  ```sh
  ntl deploy --prod
  ```

More deployment instructions [here](https://vitejs.dev/guide/static-deploy.html)