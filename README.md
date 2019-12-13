# MUI Getting Started Templates Playground 

## This repo

This is just an informal repo I've created myself in order to run [MUI Getting Started React Templates](https://material-ui.com/getting-started/templates/) on top of the [MUI Next.js example app](https://github.com/mui-org/material-ui/tree/master/examples/nextjs#nextjs-example).

The former states:

> The templates can be combined with one of the example applications to form a complete starter. 
>
> Sections of each layout are clearly defined either by comments or use of separate files, making it simple to extract parts of a page (such as a "hero unit", or footer, for example) for reuse in other pages. For multi-part examples, a table in the README at the linked source code location describes the purpose of each file.

However it wasn't so straightforward for me to run some of them on the basis of the Next.js example app, so I just created a simple self-documenting way of running them on a per needed basis. Each template gets its own link (see Home page).

Included so far:

- [ ] Dashboard
- [ ] Sign-In
- [ ] Sign-In Side
- [ ] Sign-Up
- [x] Blog (without markdown)
- [ ] Blog (with markdown-to-jsx as per original template)
- [ ] Checkout
- [x] Album
- [x] Pricing
- [x] Sticky Footer

Pull requests welcome!

Note: I still haven't been able to run the markdown-to-jsx component in the Blog example. Not sure what webpack instructions to include in next config file.

## Next.js example. How to use.

Download the example [or clone the repo](https://github.com/mui-org/material-ui):

```sh
curl https://codeload.github.com/mui-org/material-ui/tar.gz/master | tar -xz --strip=2  material-ui-master/examples/nextjs
cd nextjs
```

Install it and run:

```sh
npm install
npm run dev
```

### The idea behind the example

[Next.js](https://github.com/zeit/next.js) is a framework for server-rendered React apps.
