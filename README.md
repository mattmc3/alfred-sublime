Open with Sublime Text (Alfred workflow).
-----------------------------------------

Open files or a folders in [Sublime Text](http://www.sublimetext.com/) by using an Alfred keyword, when files or folders are selected in either Finder, or [Path Finder](http://www.cocoatech.com/pathfinder/).

By default, the keyword is set to `edit`. 

We choose not to assign the keyword of `subl`, so that there will be no confusion as to whether sublime text is to be opened, or this workflow is to be triggered. This can be changed easily by editing the keyword in the workflow.


### Behavior.

When the workflow is triggered, you must be in either Finder, or Path Finder. We will refer to Finder or Path Finder, collectively, as the "file managers". If you are not in a file manager, the workflow will silently bail as it is expected that opening files is not your current intention.

If you are in a file manager, then all currently selected items in Finder or Path Finder will be opened in Sublime Text. If no selection is present, the workflow will attempt to open the current directory.