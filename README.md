# Juiced

Juiced is flexible CSS front-end framework that has many improvments over 
existing Grid-based CSS frameworks.  It is built on the Flexible Boxes
 Layout spec and is supported by all modern browsers IE10+.


## Installation

Juiced can be downloaded directly from the Github repository <https://github.com/ovdojoey/Juiced> or through Bower using `bower install juiced`.  


## Customization

To create your own custom version of Juiced (using your own colors or breakpoints) you will need Node installed.  Once Node is on your machine, open Console and `cd` to the folder where Juiced is located. Run `npm install` to install the required depenendencies.  After that you can modify the variables in /sass/_variables.scss and run `gulp` to compile a new build and watch for changes.  Your  build will be placed in the `/dist/css/` folder.

## Usage

#### Simple Usage
You can use Juiced by including the minified `/dist/css/juiced.css` file directly in head of your webpage.

#### Advanced Usage

If you are already using SASS in your workflow, add Juiced to the top of your SASS file by using `@import /bower_components/sass/juiced`. *Note: the location of your bower components folder may vary.*  

You should define your custom Juiced variables before the `@import` as this will allow your custom variables to remain even after updating the Juiced source (using `bower update`).  *See /sass/_variables.scss for a list of available variables.*

## Learning Juiced
More to be come here, but get started with Juiced by checking out the examples folder.