# Keyboard Maestro Macros

## Installation
Download the macro and double-click the .kmmacros file in your Downloads folder to add it to Keyboard Maestro.

## Macro Details

### Find in OmniFocus
Activates a custom perspective called *All* that displays all remaining tasks in the OmniFocus database and activates the Find field in the toolbar ready for your search. You'll need to create the custom perspective in OmniFocus. See [johnscullen.com/find-in-omnifocus](http://johnscullen.com/find-in-omnifocus) for details.

The macro can be triggered from any application and will launch OmniFocus if it's not already running.

### Find in OmniFocus (standard)
Achieves the same result as *Find in OmniFocus* without using a custom perspective. Use this version if you have the Standard edition of OmniFocus (works in Pro edition too).

Activates the built-in *Projects* perspective, selects all projects, and activates the Find field in the toolbar ready for your search. See [johnscullen.com/find-in-omnifocus-part2](http://johnscullen.com/find-in-omnifocus-part2) for details.

The macro can be triggered from any application and will launch OmniFocus if it's not already running.

### OmniFocus - Show quick entry window
This avoids the problem of hitting your quick entry shortcut and nothing happening because OmniFocus isn't running. Launches OmniFocus if needed and displays the Quick Entry window to capture a new task.

### Convert - Trim path for Dropbox folders
Trims parent folders above the top level Dropbox folder from a file path. See [how to perform clipboard manipulation magic with Keyboard Maestro](http://johnscullen.com/text-manipulation-magic/) for a more detailed explanation.

### Convert - Rewrite markdown links to external sites as HTML
Rewrites inline markdown links that refer to sites outside the specified domain as HTML so they open in a new browser tab. See [how to perform clipboard manipulation magic with Keyboard Maestro](http://johnscullen.com/text-manipulation-magic/) for a more detailed explanation.

### Convert - Smart paste
Triggers one of the other *Convert* macros based on the contents of the clipboard. See [how to perform clipboard manipulation magic with Keyboard Maestro](http://johnscullen.com/text-manipulation-magic/) for a more detailed explanation.
