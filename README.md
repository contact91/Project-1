# DCI Boilerplate

Development server powered by [parcel](https://parceljs.org/) with sass compilation and auto-reload.

## Get Started

- [Setup](#setup)
- [Useful Commands](#useful-commands)
- [Project Structure](#project-structure)
- [Credits](#credits)

## Setup

1. Clone this repository into a new project folder

2. Install the dependencies

   ```
   npm install
   ```

3. Happy Coding!

## Useful Commands

### Development

Run **parcel-live-server** and start coding!

```
npm start
```

### Production

Compile source code from **src** and create an optimized production bundle in **dist** folder ready for **deployment**.

```
npm run build
```

## Project Structure

Any project created with this boilerplate will follow the structure below:

```
Project
│   README.md
│   package.json
|   package-lock.json
└───src
│   │   index.html
│   |   sassy-css.scss
|   └───images
└───dist
```


### `package.json` & `package-lock.json`

These files contain various information about your project and its dependencies, as well as useful scripts to help you with the development process.

### `src` & `index.html`

The `src` folder contains any file you would want to add to your website. **This is the main folder you will be working in**.

`index.html` is the main page for your website which you will be working on. Feel free to add any new `html` pages you create directly in the `src` folder.

### `main.scss`

The `main.scss` file will contain any `scss` code you will be writing.

### `dist`

The `dist` folder will be automatically generated whenever your run the start or build script:

```bash
npm start
npm run build
```

`npm start` will create a non optimized bundle and `npm run build` will create an optimized production bundle, ready to be deployed. It is excluded from `git` tracking since it is not customary to include compiled code in a development project.
