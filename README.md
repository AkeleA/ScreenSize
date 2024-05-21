## Screen Size Measurement App

This is a simple Svelte app that measures the width and height of the screen and displays it to the user.

### Getting Started

To get started with this project, follow these steps:

1.  Clone the repository:

bash

`git clone https://github.com/yourusername/screen-size-measurement.git`

1.  Install the dependencies:

bash


`cd screen-size-measurement` 
`npm  install`

1.  Start the development server:

bash

`npm run dev`

1.  Open your browser and navigate to `http://localhost:5000` to see the app in action.

### Folder Structure


### Code Examples

Here's an example of the `ScreenSize.svelte` component that measures the screen size and displays it to the user:

html



`<script  lang="ts">
let width =  window.innerWidth;
let height =  window.innerHeight;
function  updateDimensions()  {  width =  window.innerWidth;   height =  window.innerHeight;   }  window.addEventListener('resize', updateDimensions);  </script> 
<div  class="text-center">  <h1  class="text-4xl font-bold mb-4">Screen Size</h1>   <p  class="text-xl">   Width: {width}px<br  />     Height: {height}px
 </p>  </div>`

This component uses JavaScript to measure the screen size and updates the `width` and `height` variables accordingly. It also adds an event listener to the `resize` event to update the screen size whenever the window is resized.

The `div` element uses Tailwind CSS classes to style the text and center it on the page.


### Conclusion

This project demonstrates how to build a simple one-page application with Svelte and Tailwind CSS that measures the screen size and displays it to the user. It also shows how to
