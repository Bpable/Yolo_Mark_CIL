# Yolo_mark

* To compile on Linux simply type in console the following commands commands:
    cmake .
    make

1. To test run the standard line.
  * **on Linux:** `./linux_mark.sh`

#### Updates from previous version
1. Their is now a display of the current amoutn of labels. Notice near the right corner the Label: X. This updates accordingly, and responds when you add or delete a label.

2. Their is now a minimum size for the lenght and width of an label created. This is currently set at 10 pixels. If you draw under this for either side it will resize up to 10 pixels.

3. Some of the font has been adjusted so its easier to locate folders in the preview. Adjustments will be made in the future, but plan for all naming conventions to be within 13 characters.

4. This has also been changed from c++11 to c++17. So ensure that those are installed on your computer.

5. You can now delete images from yolo_mark itself. See below the keyboard shortcuts. **It may leave an after text file however this is zero bytes.** So when you are done labeling or checking your data. You can sort by size and delete all 0 byte files. This will be fixed in the near future.

#### Keyboard Shortcuts

Shortcut | Description | 
--- | --- |
<kbd>→</kbd> | Next image |
<kbd>←</kbd> | Previous image |
<kbd>r</kbd> | Delete selected box (mouse hovered) |
<kbd>c</kbd> | Clear all marks on the current image |
<kbd>p</kbd> | Copy previous mark |
<kbd>o</kbd> | Track objects |
<kbd>ESC</kbd> | Close application |
<kbd>n</kbd> | One object per image |
<kbd>0-9</kbd> | Object id |
<kbd>m</kbd> | Show coords |
<kbd>w</kbd> | Line width |
<kbd>k</kbd> | Hide object name |
<kbd>h</kbd> | Help |
<kbd>d</kbd> | delete_file |

