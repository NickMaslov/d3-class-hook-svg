### Description 

D3.js is one of the most popular JavaScript libraries for data visualization and is used widely with React. When creating these visualizations using D3 and React, the component often needs to have internal state and as a result are Class components. It is very difficult to have these graphs as functional components.

However, with the introduction of Hooks and supporting SVC elements, we now have a way to create these visualizations as functional components and no longer have to deal with Class components (down with classes)!

This data variable is passed to the 3 components below.

1. PieClass → A class component that will render a Pie Graph
2. PieHooks → A functional component using hooks that will render a Pie Graph
3. PieSVG → A Pie Graph using just SVG elements (supported since React 16.6)


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

