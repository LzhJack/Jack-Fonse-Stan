---
layout: default
title: Troubleshooting
nav_order: 4
---

# Troubleshooting

|  **Symptoms** | **Probable Cause** |   **Action**  |
|:-------------:|:------------------:|:-------------:|
| Cannot drag image from smaller window to the canvas | The layer is locked | On the image's layer panel, click the padlock icon |
| Error message "Could not complete your request because the smart object is not directly editable" appears | The image loaded in as a smart image | On the layer panel, right click then click _Rasterize Layer_ |
| Magic Wand selects the whole image | Tolerance is set too high | Lower the tolerance of the Magic Wand tool near the top of the window |
| Animation plays backwards | Layers or frames are not ordered appropriately | Click on the menu button in Timeline panel, and select _Reverse Frames_, or order layers in ascending order before creating frames from layers|
| Save for Web Error | Damaged Preferences | Reset Photoshop preferences by clicking on _Edit > Preferences > General_, and then click on _Reset Preferences On Quit_ |
| Frames stack ontop of each other when exported | _Do Not Dispose_ turned on | Select all frames, right click, and select _Dispose_ in the Timeline panel |
