#README

------------------------
## SET-UP .GITIGNORE
- [X] .gitignore added.
- [ ] Run in terminal:  
	git config --global core.excludesfile ~/.gitignore_global
- [ ] Delete .gitignore section from README.md
------------------------

# IIFE, XHRs and Callbacks, Oh My
https://github.com/nashville-software-school/front-end-milestones/edit/master/2-single-page-applications/exercises/SP_JS_XHR_MIND_MELTING.md

## Requirements
- [X] Create two JSON files. Each with an array: 1. carnivores, 2. herbivores.
- [X] Create an IIFE with the name of `Predator`.
	- [X] Predator should have two private arrays to store carnivores and herbivores.

	- [ ] Predator should expose two public functions to load each JSON file and store the array of animals in the appropriate private array. 
	- Each of those functions should accept one argument that will store the callback function to be executed.

- [ ] In the `iife-xhr.js` file, define two functions that will be executed after each type of animal is loaded then display those animals in your DOM. (Example given below)
- [ ] In the Predator IIFE, invoke the callback function, passed in from `iife-xhr.js`, after each file is loaded.


