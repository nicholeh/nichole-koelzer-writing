---
created: 2025-05-01T11:57:51
modified: 2025-05-14T15:23:34
title: Typography Variables in Figma
status: seedling
linked:
  - "[[Figma]]"
  - "[[Styling]]"
  - "[[Development Tools]]"
permalink: typography-variables-in-figma
---

I typically group all of the following variables under `typography`.

```
typography
 | - font-face
	 | - ...
 | - display-1
 | - display-2
 | - heading-1
 | - heading-2
 | - body-1
 | - body-2
```

## Variables to set up

### `font-face` aka Define Your Font Families

`text` variable

In programming, any time you find yourself repeating the same string value over and over again, eventually the neurons start firing and your best practice voice pipes up and says, "What if we just store this string in a variable so we only have to edit it in one place instead of across the entire code base?".

Well, that's what this variable is for.  Within the `font-face` group, I define the variab

```
typography
 | - font-face
	 | - display
	 | - heading
	 | - body
```

> [!note]
> `@font-face` is a CSS at-rule used to define fonts that are used in a UI. I use `font-face` as the variable name here because it serves a similar purpose as it would in CSS.
> That and developers can use this variable to define the name of the font in an `@font-face` ruleset.




I use this when creating different themes that utilize multiple font families.




## See Also

- [[Using Figma Variables to Create a Design System]]