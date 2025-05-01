---
title: Using Obsidian to Manage Content in Astro
modified: May 01, 2025, 10:20 am
---

# Using Obsidian to Manage Content in Astro

## Figuring out what content should be managed in Astro.

I do not want to manage all content in Astro, just the digital garden portion. So I set up my vault in `/writing/` with a subfolder called `/assets/` to hold any assets that will be used in posts.

1. Open `/writing/` folder as a new vault in Obsidian using the "Open folder as Vault" option (if you already have this set up in your repo).
2. Install all the plugins and themes. See [[How I set up Obsidian]].
3. Install

There appears to be three ways to do this:

1. Put the vault in the repo
2. Put the vault elsewhere on my computer, then use submodules to pull it in.
3. Astro [content collections](https://docs.astro.build/en/guides/content-collections/)
