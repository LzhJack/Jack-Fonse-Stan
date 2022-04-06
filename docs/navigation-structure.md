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

1. On the top bar of photoshop, click _File_, then in the dropdown click _New_. Alternatively, you can press <kbd>Ctrl</kbd> + <kbd>N</kbd> on your keyboard. This will open the _New Document_ menu.  
![New File](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/newfile.png)

2. The right side of the menu contains the _Preset Details_, you can change the name of your photoshop file on the first line under _Preset Details_.
3. Now you need to set the width and height of your blank file. First make sure that you have chosen your preferred unit of measurement. For this tutorial, we will use centimetres.  
![preset](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/preset.png)

4. To set the width and the height of your blank file, change the fields labeled width for your file’s _canvas_, and height for your file’s height. Any width and   height is fine as long as your image can fit inside it. For this tutorial, we will be using a 16 x 9 _canvas_.
5. In order to make your image transparent later, you must click the _Background Contents_ field, and in the dropdown select _Transparent_.  
![transparent](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/transparent.png)

6. Finally, you can press _Create_ at the bottom right of the menu. You can leave the other settings as the default.

If your file looks like a blank transparent canvas like the image below, you have now successfully opened a new Photoshop file.  
![blankcanvas](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/blankcanvas.png)

---

## Image importing

For this section, you must have an image file ready to use. The image must have a plain uniform background. The image must also fit within the file created previously. For this tutorial, we have picked this sample image of Kirby riding a star.  
![Kirby](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/kirb-star.jpg)

1. To open the image click _File_, and in the dropdown menu click _Open_. Alternatively you can press <kbd>Ctrl</kbd> + <kbd>O</kbd> on your keyboard. This will open up your file explorer.  
![New Image](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/newimage.png)

2. Inside the file explorer, locate and click on your image. You can also type in the filename at the bottom of the window if the image is located in the current directory.
3. At the bottom left of the file explorer, click the _Open_ button. The image will now load on a new tab in Photoshop.
4. At the bottom-right corner of Photoshop, make sure that you are in the _Layers_ panel. If not,  click the label named _Layers_.  
![layertab](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/layertab.png)

5. The layers panel shows all of the layers in your current file. Right now, there should only be one layer. If it is not yet highlighted by a lighter grey color, you must click on it. You can click once on either the small icon, or the name of the layer.  
![selectlayer](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/selectlayer.png)

6. On the very left side of Photoshop is the _toolbar_. The toolbar contains different tools to edit or create graphics. For now, click on the very first one that looks like four perpendicular arrows pointing away from each other. You can also press <kbd>V</kbd> on your keyboard. This tool is called the _Move_ tool. This lets you move your image on the canvas.  
![move](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/move.png)

7. Now we need to put the image on the file we made previously. Right click on the tab of the image file, then in the dropdown click _Move To New Window_. This should separate the image into a smaller window.  
![newwindow](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/newwindow.png)

8. Go back to the blank Photoshop file made in the section before. Make sure that you are still using the _Move_ tool. Now drag your image from the smaller window into your blank canvas. You can then close the smaller window. If needed, move your image to where it is fully visible on the canvas.

When you have added your image to your canvas like below, you are now ready to remove the image’s background.  
![importedimg](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/importedimg.png)

---

## Magic wand tool

You can find many ways to remove an image’s background on Photoshop. However, for this tutorial we will use the _Magic Wand_ tool.

1. Make sure that the layer containing your image is selected.
2. On the toolbar, select the 4th tool that resembles a magic wand. You can also press <kbd>W</kbd> on your keyboard. If the 4th tool doesn’t resemble a magic wand, right click on the icon and click on _Magic Wand Tool_ in the submenu.  
![magicwand](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/magicwand.png)

> ℹ️ **Info**
> 
> This is the _Magic Wand_ tool. The _Magic Wand_ tool lets you select a big portion of similarly-coloured pixels in your canvas. This is great for removing an image’s background.  

3. You can set the _tolerance_ of the Magic Wand near the top of the application. Set the field labeled _Tolerance_ to 25. This will make sure that you only get the background and not parts of your image.  
![tolerance](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/tolerance.png)

4. With the Magic Wand tool selected, click on any part of your image’s background. This will select a portion of your image. All pixels within the moving black line are considered selected.
> ⚠️**Warning**
> 
> If some parts of the image you want to keep are selected, click _Select_ at the very top of the application. Then click on _Deselect_. You can also press 
<kbd>Ctrl</kbd> + <kbd>D</kbd>. You then have to repeat steps 3 and 4 using a lower tolerance than the one used.  
![deselect](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/deselect.png)

5. Delete the current selection by pressing <kbd>Backspace</kbd> or <kbd>Delete</kbd> on your keyboard.
6. Finally, deselect the current selection.

You have now successfully removed the background of the image like so.  
![kirbimperfect](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/kirbimperfect.png)

However, there can be parts of the image that weren't selected by the Magic Wand tool. You can try selecting it again using Magic Wand but sometimes it is not enough. You need to select parts of the image on a finer scale.

---

## Lasso selection tool

For finer selection, you should use one of the lasso tools.

1. Zoom in on the part of the image you want to select. Do this by clicking the magnifying glass icon on the toolbar. You can also press <kbd>Z</kbd>.  
![zoom](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/zoom.png)  
Then repeatedly click on the area you want to zoom in to. If you need to zoom out, click while holding <kbd>Alt</kbd>.

2. Click the 3rd tool on the toolbar resembling a lasso. This is the _Lasso_ tool. It lets you select part of the canvas by freehand.  
![lasso](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/lasso.png)
> ℹ️ **Info**
> 
> If you right click the lasso icon, you can also select either the _Polygonal Lasso_ tool, or the _Magnetic Lasso_ tool. The Polygonal Lasso tool selects by letting you place points instead of drawing by freehand. The Magnetic Lasso tool is freehand but tries to guess the location of where you’re drawing, which is great for inaccurate drawing.
  
3. Using any of these lassoes, select the part of the image to be removed. Make sure that you fully enclose the selection by clicking on the very first point placed in the selection.  
![selected](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/selected.png)
4. After closing the selection, the moving black lines should appear again. In which case, you can delete the selection by pressing <kbd>Backspace</kbd> or <kbd>Delete</kbd> on your keyboard.
5. Again, deselect the selection <kbd>Ctrl</kbd> + <kbd>D</kbd>.

Your image should now have a transparent background like the one below. Now you need to export it.  
![perfectkirby](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/perfectkirby.png)

## Image exporting

1. Click on _File_ on the very top-left of the application, then hover on _Export_ on the dropdown menu. Then click _Export As_. You can also press <kbd>Alt</kbd> + <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>W</kbd>. The _Export As_ window should appear.  
![export](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/export.png)

2. At the right side of the window, under _File Settings_, click on the _Format_ field. Then in the dropdown, click _png_.  
![png](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/png.png)

3. After selecting PNG format, check the box right below labelled _Transparency_. This will turn the exported image transparent.  
4. You can then press _Export_ at the very bottom-right of the window. You can leave the other fields as default values. This will now open the File Explorer.  
![exportbtn](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/exportbtn.png)

5. Find a place in your computer to store the new transparent image. Give the image any filename as well. Then click _Save_.

> ✔️ **Success**
> 
> Once the image has been saved. You can open the new transparent image or use it on your projects.
![donekirby](https://lzhjack.github.io/Jack-Fonse-Stan/assets/images/donekirby.png)

# Conclusion

At the end of this section, you have learned:
* How to create a new transparent photoshop file
* How to import images to photoshop files
* How to use the Magic Wand tool
* How to use the Lasso tools
* How to export images as transparent _PNG_ files

Good job! You can now proceed to learning how to animate a GIF image in Photoshop
