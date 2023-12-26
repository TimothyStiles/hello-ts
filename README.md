## hello-ts

hello-ts is a simple example repo to show how you can get started with test driven development in TypeScript.

Go has in-line running tests, debugging, and code highlighting baked into their official vscode extension but it turns out most other languages don't have code hightlighting like this by default. This repo shows how you can get started with test driven development in TypeScript with code highlighting in vs-code.

![Example screenshot of golang code from [poly](https://github.com/bebop/poly) covered by tests being highlighted green.](./screenshots/golang-gutters.png)

I'm not really a JS/TS developer but went down this rabbit hole when exploring vs-code extension development. I was surprised to find that there wasn't a simple way to get code highlighting like this for TypeScript. I'm sure there are other ways to do this but this is the simplest way I found.
 
![Example screenshot of typescript code in this repo covered by tests being highlighted green.](./screenshots/typescript-gutters.png)

All of the example code we're testing can be found in [src](./src) and comes from this article by @janis_t on twitter [article](https://www.typescriptbites.io/articles/build-test-and-publish-typescript-npm-package-2022) by [@janis_t on twitter](https://twitter.com/janis_t).


## install

This assumes you already have npm (or equivalent) and VScode installed

```git clone https://github.com/TimothyStiles/hello-ts && cd hello-ts && npm install && code .```

Then:

1. Install the recommended vs-code extensions through the dialogue that should pop up when you first open the project.
2. Close out the window
3. Reopen the project with vs-code and extensions installed.
4. Open `src/index.js`.
5. Hit `command + s`

 Now `src/index.js` should have the code gutters like in the above screenshot.

If you're into other languages, check out:

    * [hello-rs](https://github.com/TimothyStiles/hello-rs) for Rust