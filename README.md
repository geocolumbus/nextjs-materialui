This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## How this app was built

    npx create-next-app
    cd nextjs-materialui
    npm install --save @material-ui/core

see https://developerhandbook.com/react/how-to-set-up-nextjs-material-ui/

* update pages/index.js
* add _document.jsx

Configure the app to run on a different port than 3000 (if desired)

```javascript
  "scripts": {
    "dev": "next dev --port 3001",
```

Configure formatting.

Plugins -> Javascript and TypeScript -> Fix ESLint Problems  ```[opt][shift][cmd]F```

You will need an ```.editorconfig``` file.

```text
root = true

[*.{js, css, xml, html, json, scss}]
indent_style = space
indent_size = 4
tab_width = 4
trim_trailing_whitespace = true
insert_final_newline = true
```

Install eslint dependencies

```bash
npm install --save-dev eslint eslint-config-standard eslint-loader /
eslint-plugin-import eslint-plugin-node eslint-plugin-promise /
eslint-plugin-react eslint-plugin-standard
```

Install jest test library

```bash
npm install --save-dev jest jest-fetch-mock jest-localstorage-mock
```

To configure ESLint automatically in the current project, open the Settings/Preferences dialog ⌘,, go to Languages and Frameworks | JavaScript | Code Quality Tools | ESLint, and select the Automatic ESLint configuration option.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
