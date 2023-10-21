# Template Counter
Tempalte project

## Description
This project is a template for vannila js + vite + vitest setup

## Technical information
The solution is based on pure vanilla js with no libs using [Vite](https://vitejs.dev/) as a bundler.

For tests it is using [Vitest](https://vitest.dev/) that is using [WebdriverIO](https://webdriver.io/) under the hood.

## Project structure
- `components` - 0Project is using component-based approach with custom elements. Components are using `tmp-` prefix that means "template."
    - The `tmp-app` component is the main component containing the whole app.
    - The `tmp-counter` component is responsible for the counter
- `helpers` - Helper classes
    - `math.helper` - Math functions that are not defined in the default Math class
- `styles` - additional styles
    - `common` - styles that are common for the app and most likely needed in most/all components
- `main.js` - file defines all components

## Available functionality
- Increments counter
- Decrements counter

## How to run
1. Clone the repo
2. Run `npm install`
3. Run `npm run dev`

## How to run test
1. Clone the repo
2. Run `npm install`
3. Run `npm run test`
