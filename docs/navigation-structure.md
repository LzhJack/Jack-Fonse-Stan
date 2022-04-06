---
layout: default
title: Removing the Background from an Image
nav_order: 2
---

# Overview

In this section you will learn how to remove the background of an image using various selection tools. Removing an image’s background is useful for tasks such as:  
* Displaying images on websites
* Creating game assets
* Making custom icons or logos, and
* Presenting photos on powerpoint presentations.


{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Photoshop file setup

Before we edit the image, we must create a new blank file. 

1. On the top bar of photoshop, click ‘File’, then in the dropdown click ‘New’. Alternatively, you can press [Ctrl] + [N] on your keyboard. This will take open the ‘New Document’ menu.
2. The right side of the menu contains the ‘Preset Details’, you can change the name of your photoshop file on the first line under ‘Preset Details’
3. Now you need to set the width and height of your blank file. First make sure that you have chosen your preferred unit of measurement. For this tutorial, we will use centimetres.
4. To set the width and the height of your blank file, change the fields labelled width for your file’s canvas, and height for your file’s height. Any width and   height is fine as long as your image can fit inside it. For this tutorial, we will be using a 16 x 9 canvas.
5. In order to make your image transparent later, you must click the ‘Background Contents’ field, and in the dropdown select Transparent.
6. Finally, you can press ‘Create’ at the bottom right of the menu. You can leave the other settings as the default.
You have now opened a new Photoshop file.


---

## Image importing

For this section, you must have an image file ready to use. The image must have a plain uniform background. The image must also fit within the file created previously. For this tutorial, we have picked this sample image of Kirby riding a star.

1. To open the image click ‘File’, and in the dropdown menu click ‘Open’. Alternatively you can press [Ctrl] + [O] on your keyboard. This will open up your file explorer.
2. Inside the file explorer, locate and click on your image. You can also type in the filename at the bottom of the window if the image is located in the current directory.
3. At the bottom left of the file explorer, click the ‘Open’ button. The image will now load on a new tab in Photoshop.
4. At the bottom-right corner of Photoshop, make sure that you are in the ‘Layers’ panel. If not,  click the label named ‘Layers’.
5. The layers panel shows all of the layers in your current file. Right now, there should only be one layer. If it is not yet highlighted by a lighter grey color, you must click on it. You can click once on either the small icon, or the name of the layer.
6. On the very left side of Photoshop is the toolbar. The toolbar contains different tools to edit or create graphics. For now, click on the very first one that looks like four perpendicular arrows pointing away from each other. You can also press V on your keyboard. This tool is called the ‘Move’ tool. This lets you move your image on the canvas.
7. Now we need to put the image on the file we made previously. Drag the window of this file out by clicking the tab near the top of the screen, then pulling down. This should separate the image into a smaller window. 
8. Go back to the blank Photoshop file made in the section before. Make sure that you are still using the ‘Move’ tool. Now drag your image from the smaller window into your blank canvas. You can then close the smaller window. If needed, move your image to where it is fully visible on the canvas.

You are now ready to remove the image’s background.


#### Example

{: .no_toc }

```yaml
---
layout: default
title: Customization
nav_order: 4
---

```

The parameter values determine the order of the top-level pages, and of child pages with the same parent. You can reuse the same parameter values (e.g., integers starting from 1) for the child pages of different parents.

The parameter values can be numbers (integers, floats) and/or strings. When you omit `nav_order` parameters, they default to the titles of the pages, which are ordered alphabetically. Pages with numerical `nav_order` parameters always come before those with strings or default `nav_order` parameters. If you want to make the page order independent of the page titles, you can set explicit `nav_order` parameters on all pages.

By default, all Capital letters come before all lowercase letters; you can add `nav_sort: case_insensitive` in the configuration file to ignore the case. Enclosing strings in quotation marks is optional.

> _Note for users of previous versions:_ `nav_sort: case_insensitive` previously affected the ordering of numerical `nav_order` parameters: e.g., `10` came before `2`. Also, all pages with explicit `nav_order` parameters previously came before all pages with default parameters. Both were potentially confusing, and they have now been eliminated.

---

## Magic wand tool

You can find many ways to remove an image’s background on Photoshop. However, for this tutorial we will use the Magic Wand tool.

1. Make sure that the layer containing your image is selected.
2. On the toolbar, select the 4th tool that resembles a magic wand. You can also press W on your keyboard. If the 4th tool doesn’t resemble a magic wand, right click on the icon and click on ‘Magic Wand Tool’ in the submenu.
This is the ‘Magic Wand’ tool. The ‘Magic Wand’ tool lets you select a big portion of similarly-coloured pixels in your canvas. This is great for removing an image’s background.
3. You can set the tolerance of the ‘Magic Wand’ near the top of the application. Set the field labeled ‘Tolerance’ to 25. This will make sure that you only get the background and not parts of your image.
4. With the ‘Magic Wand’ tool selected, click on any part of your image’s background. This will ‘select’ a portion of your image. All pixels within the moving black line are considered selected.
5. If some parts of the image you want to keep are selected, click ‘Select’ at the very top of the application. Then click on ‘Deselect’. You can also press Ctrl + D. You then have to repeat steps 3 and 4 using a lower tolerance than the one used.
6. Delete the current selection by pressing Backspace or Delete on your keyboard.
7. Deselect the selection by clicking ‘Select’ at the very top of the application. Then click on ‘Deselect’. You can also press Ctrl + D on your keyboard.

You have now successfully removed the background of the image. However, there can be parts of the image that weren't selected by the ‘Magic Wand’ tool. You can try selecting it again using ‘Magic Wand’ but sometimes it is not enough. You need to select parts of the image on a finer scale.


#### Example

{: .no_toc }

```yaml
---
layout: default
title: 404
nav_exclude: true
---

```

The `nav_exclude` parameter does not affect the [auto-generating list of child pages](#auto-generating-table-of-contents), which you can use to access pages excluded from the main navigation.

Pages with no `title` are automatically excluded from the navigation.

---

## Lasso selection tool

For finer selection, you should use one of the lasso tools.

1. Zoom in on the part of the image you want to select. Do this by clicking the magnifying glass icon on the toolbar. You can also press Z. Then repeatedly click on the area you want to zoom in to. If you need to zoom out, click while holding Alt.
2. Click the 3rd tool on the toolbar resembling a lasso. This is the Lasso tool. It lets you select part of the canvas by freehand. If you right click the lasso icon, you can also select either the Polygonal Lasso tool, or the Magnetic Lasso tool. The Polygonal Lasso tool selects by letting you place points instead of drawing by freehand. The Magnetic Lasso tool is freehand but tries to guess the location of where you’re drawing, which is great for inaccurate drawing.
3. Using any of these lassoes, ‘select’ the part of the image to be removed. Make sure that you fully enclose the selection by clicking on the very first point placed in the selection. 
4. After closing the selection, the moving black lines should appear again. In which case, you can delete the selection by pressing Backspace or Delete on your keyboard.
5. select the selection by clicking ‘Select’ at the very top of the application. Then click on ‘Deselect’. You can also press Ctrl + D on your keyboard.

You have now removed the background of your image. Now you need to export it.


```
+-- ..
|-- (Jekyll files)
|
|-- docs
|   |-- ui-components
|   |   |-- index.md  (parent page)
|   |   |-- buttons.md
|   |   |-- code.md
|   |   |-- labels.md
|   |   |-- tables.md
|   |   +-- typography.md
|   |
|   |-- utilities
|   |   |-- index.md      (parent page)
|   |   |-- color.md
|   |   |-- layout.md
|   |   |-- responsive-modifiers.md
|   |   +-- typography.md
|   |
|   |-- (other md files, pages with no children)
|   +-- ..
|
|-- (Jekyll files)
+-- ..
```

On the parent pages, add this YAML front matter parameter:

- `has_children: true` (tells us that this is a parent page)

#### Example

{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
---

```

Here we're setting up the UI Components landing page that is available at `/docs/ui-components`, which has children and is ordered second in the main nav.

### Child pages

{: .text-gamma }

On child pages, simply set the `parent:` YAML front matter to whatever the parent's page title is and set a nav order (this number is now scoped within the section).

#### Example

{: .no_toc }

```yaml
---
layout: default
title: Buttons
parent: UI Components
nav_order: 2
---

```

The Buttons page appears as a child of UI Components and appears second in the UI Components section.

### Auto-generating Table of Contents

By default, all pages with children will automatically append a Table of Contents which lists the child pages after the parent page's content. To disable this auto Table of Contents, set `has_toc: false` in the parent page's YAML front matter.

#### Example

{: .no_toc }

```yaml
---
layout: default
title: UI Components
nav_order: 2
has_children: true
has_toc: false
---

```

### Children with children

{: .text-gamma }

Child pages can also have children (grandchildren). This is achieved by using a similar pattern on the child and grandchild pages.

1. Add the `has_children` attribute to the child
1. Add the `parent` and `grand_parent` attribute to the grandchild

#### Example

{: .no_toc }

```yaml
---
layout: default
title: Buttons
parent: UI Components
nav_order: 2
has_children: true
---

```

```yaml
---
layout: default
title: Buttons Child Page
parent: Buttons
grand_parent: UI Components
nav_order: 1
---

```

This would create the following navigation structure:

```
+-- ..
|
|-- UI Components
|   |-- ..
|   |
|   |-- Buttons
|   |   |-- Button Child Page
|   |
|   |-- ..
|
+-- ..
```

---

## Image exporting

1. Click on ‘File’ on the very top-left of the application, then hover on ‘Export’ on the dropdown menu. Then click ‘Export As’. You can also press Alt + Shift + Ctrl + W. The ‘Export As’ window should appear.
2. At the right side of the window, under ‘File Settings’, click on the ‘Format’ field. Then in the dropdown, click PNG. This will turn the exported image transparent.
3. You can then press ‘Export’ at the very bottom-right of the window. You can leave the other fields as default values. This will now open the File Explorer.
4. Find a place in your computer to store the new transparent image. Give the image any filename as well. Then click ‘Save’.

Success: Once the image has been saved. You can open the new transparent image or use it on your projects.


#### Example

{: .no_toc }

```yaml
# Aux links for the upper right navigation
aux_links:
  "Just the Docs on GitHub":
    - "//github.com/just-the-docs/just-the-docs"
```

---

## In-page navigation with Table of Contents

To generate a Table of Contents on your docs pages, you can use the `{:toc}` method from Kramdown, immediately after an `<ol>` in Markdown. This will automatically generate an ordered list of anchor links to various sections of the page based on headings and heading levels. There may be occasions where you're using a heading and you don't want it to show up in the TOC, so to skip a particular heading use the `{: .no_toc }` CSS class.

#### Example

{: .no_toc }

```markdown
# Navigation Structure

{: .no_toc }

## Table of contents

{: .no_toc .text-delta }

1. TOC
   {:toc}
```

This example skips the page name heading (`#`) from the TOC, as well as the heading for the Table of Contents itself (`##`) because it is redundant, followed by the table of contents itself. To get an unordered list, replace `1. TOC` above by `- TOC`.

### Collapsible Table of Contents

The Table of Contents can be made collapsible using the `<details>` and `<summary>` elements , as in the following example. The attribute `open` (expands the Table of Contents by default) and the styling with `{: .text-delta }` are optional.

```markdown
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
```

The result is shown at [the top of this page](#navigation-structure) (`{:toc}` can be used only once on each page).
