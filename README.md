# next-netlify-template

* change `"name"` in `package.json`
* run:
```
mkdir public

yarn add next react react-dom
yarn add -D typescript @types/react @types/node

yarn dev
```
* optional: remove README.md and LICENSE

* on Netlify UI:
  - build command: `yarn build`
  - publish directory: `out`
  - install [`Next on Netlify` plugin](https://app.netlify.com/plugins/@netlify/plugin-nextjs/install)
  - install [`Next.js Cache` plugin](https://app.netlify.com/plugins/netlify-plugin-cache-nextjs/install)
