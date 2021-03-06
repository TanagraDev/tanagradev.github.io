---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Content
parent: Instructions
grand_parent: Docs
nav_order: 5
permalink: /docs/instructions/content.html
---

# Content
## Write Your Book's Content

With your outline converted into a directory and file structure in the `content/` directory, you're now ready to begin authoring your book based on the outline you created. Continuing with the previous examples, you should have a book structure like we predicted on the [Outline documentation](outline.html):

- *Part 0 - Part Title/*
   - **Chapter 0 - Chapter Title.md**
   ```
      # Chapter 0 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - **Chapter 1 - Chapter Title.md**
   ```
      # Chapter 1 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - *Part 0 - Part Title_media/*
      - [media files for part 0 go here]
- *Part 1 - Part Title/*
   - **Chapter 2 - Chapter Title.md**
   ```
      # Chapter 2 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - **Chapter 3 - Chapter Title.md**
   ```
      # Chapter 3 - Chapter Title

      ## Section Title

      ### Subsection Title

      ## Section Title

      ### Subsection Title
   ```
   - *Part 1 - Part Title_media/*
      - [media files for part 1 go here]

## Writing Text
In each of these markdown files (\*.md), you can use [GitHub's markdown style](https://guides.github.com/features/mastering-markdown/) to write your book under each chapeter, section, and subsection.

Here are a few examples for quick reference:

```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Unordered List Item 1
* Unordered List Item 2
  * Unordered List Item 2a
  * Unordered List Item 2b

1. Ordered List Item 1
1. Ordered List Item 2
1. Ordered List Item 3
   1. Ordered List Item 3a
   1. Ordered List Item 3b

https://www.tanagra.dev << These links are automatic
[Tanagra](https://www.tanagra.dev)
```

The above text would render like this:

---

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

* Unordered List Item 1
* Unordered List Item 2
  * Unordered List Item 2a
  * Unordered List Item 2b

1. Ordered List Item 1
1. Ordered List Item 2
1. Ordered List Item 3
   1. Ordered List Item 3a
   1. Ordered List Item 3b

https://www.tanagra.dev << These links are automatic
[Tanagra](https://www.tanagra.dev)

---

## Media
As we saw above, the `tanagra convert` command will generate a directory for media in each book part directory. Place your media files for each respective book part in that media directory and then reference them using a local/relative reference. For example:

For an image in *part 0* of your book...
- `![Dogs doing magic!](Part 0 - Part Title_media/dogs_doing_magic.png)`

For an image in *part 1* of your book...
- `![Sleight of paw magic](Part 1 - Part Title_media/sleight_of_paw.png)`

## Next Steps
When you've completed authoring the markdown of your book, you can [compile your markdown into a rendered book](compile.html).
