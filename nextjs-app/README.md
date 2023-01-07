# Next.js example app

* [Next.js](https://nextjs.org/)
* Bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app)

## Setup

```
➜  typescript-all-the-things git:(main) ✗ npx create-next-app@latest --typescript
npx: installed 1 in 0.983s
✔ What is your project named? … nextjs-app
✔ Would you like to use ESLint with this project? … No / Yes
Creating a new Next.js app in /home/christoph/git/jerolimov/typescript-all-the-things/nextjs-app.

Using npm.

Installing dependencies:
- react
- react-dom
- next
- @next/font
- typescript
- @types/react
- @types/node
- @types/react-dom
- eslint
- eslint-config-next
+ @types/react@18.0.26
+ eslint-config-next@13.1.1
+ react@18.2.0
+ react-dom@18.2.0
+ @types/node@18.11.18
+ typescript@4.9.4
+ next@13.1.1
+ eslint@8.31.0
+ @types/react-dom@18.0.10
+ @next/font@13.1.1
added 265 packages from 235 contributors and audited 276 packages in 26.273s

95 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities


Initializing project with template: default 

Success! Created nextjs-app at nextjs-app
```

## Dependencies

* next cli
* TypeScript and some type definitions
* eslint

## Project structure

```
pages
public
styles
.eslintrc.son
next-env.d.ts
next.config.js
package.json
tsconfig.json
```

## Available Scripts

* `npm run dev`, automatically opens [http://localhost:3000](http://localhost:3000)
* `npm run build`
* `npm run start`
* `npm run lint`

Edit `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

* [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
* [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
* You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/)
* Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
