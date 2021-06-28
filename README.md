# Svelte Web Component 🎉

This is a slightly modified [Svelte](https://svelte.dev/) web component template based on the template from https://github.com/stefanonepa/svelte-component-ts. It includes [Bulma](https://bulma.io/) via a CDN. Use this template to create CodeVA Connect web components (at least until we figure out something better).

## Prerequisites

You need the following software to create web components based on this template:

* NPM (Node Package Manager)
* A text editor (I use [Visual Studio Code](https://code.visualstudio.com/))

I recommended that you get comfortable with the following topics as well (but if you want to learn this stuff while doing this project, that's also probably fine):

* Writing HTML, CSS & Javascript
* Using the command line
* Creating and developing NodeJS projects using NPM or Yarn
* Using a CSS framework (this one uses [Bulma](https://bulma.io/), but if you've used something else like [Bootstrap](https://getbootstrap.com/) you'll be alright)

## Setup

Clone (make a copy) of the source code by with [degit](https://github.com/Rich-Harris/degit). Open a command prompt, enter the following command (you can replace `my-new-component` with a name of your choice), and press `Enter`:

```bash
npx degit CodeVA-Curriculum/webcomponent-boilerplate my-new-component
```

Next, you'll need to install all the required Javascript packages to run the project. First, use your command prompt to enter the project folder:

```bash
cd my-new-component
```

Then, use either `yarn` or `npm` to install the project packages from the list in the `package.json` file (you don't need to open the file or anything; the package manager looks at that file for you). If you haven't used `yarn` before, you can run the following command in your command prompt (make sure you have entered the project folder in the previous step, otherwise this won't work):

```bash
npm install
```

**Optionally Use Yarn Instead:** I use `yarn` for these kinds of thing because I generally find that it works a little better. If you haven't used `yarn` before, you'll need to install it by entering the following command in your command prompt (it doesn't matter where your command prompt "is"; this command installs `yarn` for your whole computer):

```bash
npm install -g yarn
```

Then, you can use `yarn` instead of `npm` to install all the Javascript packages for your project. Enter the following command into your command prompt, making sure you've followed the above step to enter your project folder (otherwise this won't work, because there wouldn't be a `package.json` file to base the install procedure off of):

```bash
yarn
```

Finally, you can use `yarn` or `npm` to run your development server and view the starter web component in your browser.

**NPM**
```bash
npm run dev
```

**Yarn**
```
yarn dev
```

You'll see output in your command prompt indicating that the project is being served from `localhost:5000` (if your computer is using port `5000` for something else, it will be a different number). Visit `localhost:5000` in a web browser to view the web component.

## Adding to the Boilerplate

You can develop the rest of the component using conventional [Svelte](https://svelte.dev/). If you aren't familiar with Svelte, they have a great [tutorial](https://svelte.dev/tutorial/basics) that walks you through the basics.

Bulma classes are available globally in all components; check out the documentation [here](https://bulma.io/documentation/).
