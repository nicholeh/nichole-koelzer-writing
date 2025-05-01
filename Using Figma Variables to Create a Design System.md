---
created: 2025-05-01T11:57:51
modified: 2025-05-01T16:19:20
title: Using Figma Variables to Create a Design System
status: idea
linked:
  - "[[Figma]]"
  - "[[Styling]]"
  - "[[Development Tools]]"
permalink: Using Figma Variables to Create a Design System
---

> [!todo]
> - [ ] Style Dictionary Export
> - [ ] Dealing with Typography

## Accessing Variables in Figma

==How to find in Figma.==

## Setting up Color Tokens

1. Setup your base colors in variables. I like to do something like:

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

2. Once that is done, I create the named variables for the design system. The name of the variable refers to the function, where as the value is the color it should be. 
   
   In the following example, `ink/base` is the name of the variable and the value is an [alias](https://help.figma.com/hc/en-us/articles/15145852043927-Create-and-manage-variables-and-collections#alias) to the `color/grey/500` swatch that we created in step one.

```
ink/base: color/grey/500
```


## Color Modes

==Benefits==
- light & dark mode obv
- inverted colors - think different sections of a web page. One may have a light background, and the next section has a dark.
- Creating multiple themes (like cappucinn)

==How to implement in Figma==

> [!note] This is not possible in the free version. You have to have a full seat to do this.

## References

- [Create and manage variables and collections – Figma Learn - Help Center](https://help.figma.com/hc/en-us/articles/15145852043927-Create-and-manage-variables-and-collections#01H8044A3JKE9Q769Z1926VE4A)

