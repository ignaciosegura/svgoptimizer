# svgoptimizer
SVG files optimizer. Put anything on an INPUT folder and get it, optimized for production, in the OUTPUT folder.

# Requirements
This is a Node.JS script. It has been tested in Node.JS 11. It should work on any ES6 enabled Node version.

# Install

npm install

# Usage

## Simple

npm run process -> Processes all SVG files in INPUT folder and creates optimized copies in the OUTPUT folder.

npm run watch -> Same as before, but it keeps watching the INPUT folder, so when you add a new file there, it is immediately processed.

## Custom

npm run watch --input [input_folder] --output [output_folder] --settings [settings_file]

Default values are:

Input folder: input
Output folder: output
Settings file: svg-optimize-default.json
