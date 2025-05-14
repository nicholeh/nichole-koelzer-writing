---
created: 2025-05-01T11:57:51
modified: 2025-05-14T14:52:46
title: Using Figma Variables to Create a Design System
status: seedling
linked:
  - "[[Figma]]"
  - "[[Styling]]"
  - "[[Development Tools]]"
permalink: using-figma-variables-to-create-a-design-system
---

> [!todo]
> - [ ] Style Dictionary Export
> - [ ] Dealing with Typography
> - [ ] Gradients and variables

## Accessing Variables in Figma

 While setting up variables in Figma does require effort, the work pays off in the long run.

==How to find in Figma.==

## Setting up Variables

- [[Typography Variables in Figma]]


## Setting up Color Tokens

1. Set up your base colors in variables. I like to do something like:

```
color/
  grey/
	- 000
	- 100
	- 200
	- 300
	- 400
	- 500
  goldenrod/
	- 000
	- 100
	- 200
	- 300
	- 400
	- 500
``` 

2. Once that is done, I create the "named variables" for the design system. When I use the phrase "named variables," I'm referring to variables that are named based on the function they will be used for (`surface/primary`) versus what they represent (`color/white`).
   
   In the following example, `ink/base` is the name of the variable, and the value is an [alias](https://help.figma.com/hc/en-us/articles/15145852043927-Create-and-manage-variables-and-collections#alias)^[Aliases allow you to assign variables to variables in Figma.] to the `color/grey/500` swatch that we created in step one.

```
ink/base: color/grey/500
```

### Naming tokens so they make sense for you and the developer

==How do?==

## Modes

In my opinion, modes are where variables truly shine, allowing you to flip between different themes instantly.

==Benefits==
- light & dark mode obv
- Inverted colors - think of different sections of a web page. One section may have a light background, and the next section has a dark one.
- Creating multiple themes (like cappucinn)

==How to implement in Figma==

> [!note] This is not possible in the free version. You have to have a full seat to do this.

## References

- [Create and manage variables and collections – Figma Learn - Help Center](https://help.figma.com/hc/en-us/articles/15145852043927-Create-and-manage-variables-and-collections#01H8044A3JKE9Q769Z1926VE4A)

