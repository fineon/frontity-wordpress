# Frontity behaviour and code structure documentation

Frontity, is a React framework aimed at building a front-end app for headless Wordpress.

As I'm learning how to use the framework, i'll documenting some of the behaviours seen in a typical project

## Purpose of this doc
- To elaborate on Frontity guides and usage, with perspective from a JS developer

## When to use this doc
- 

## Who should read this documentation
- Developers
- Tech users who are enthusiastic about using Javascript AJAX and JSON to their advantage when building their own WordPress sites, instead of relying on PHP

## Knowledge prerequisite
Since Frontity relies on React, ES5, ES6 Javascript syntaxes, developers should have a clear understanding of these concepts

- React.js
	- React Hooks
- Node.js
- Javascript 
	- object/array destructuring ->
	- import/export module -> you can use `import`/`export default` Javascript variables, functions in a `.js` file then use them in other files
	- arrow functions -> just a normal JS function, but with *this* context escaped. Syntax: ```const myFunctionInMultipleLines = (parameter1, parameter2) => {
	// multiple lines of code block here. Need to use the `return` statement to return values
}``` or all in 1 line: `const myFunctionInOneLine = parameter => //code block here. Will auto return the value
	- *this* context
- API calls and AJAX
- JSON
- CSS
- HTML

## Tech stack used by Frontity
- Emotion CSS library
- React Helmet for setting HTML `head`
- React.js 
- Node.js