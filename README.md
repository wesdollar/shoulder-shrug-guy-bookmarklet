# Shoulder Shrug Guy Bookmarklet
Simple bookmarklet to easily copy shoulder shrug guy to your clipboard for use wherever. 

## Use
Bookmarklet to open a default browser alert dialog containing the text to copy that makes up the popular shoulder shrug guy kaomoji. Simply press ctrl + c to copy to clipboard then press 'enter' to close the dialog box. Paste the shruggie anywhere your heart so desires.

## Installation (specific to Chrome but easily adapted to others)
1. Right-click on bookmark toolbar, select "Add page," or add page from within your browser's bookmark manager.
2. Enter any name you want into the bookmark name field.
3. Copy the contents of shruggie.js to your clipboard.
4. Paste the contents of shurggie.js into the URL field of the bookmark, prefaced with "javascript:" (without the quotes)
5. Press Save

## Bookmark Setup URL
    javascript:(function() { return window.prompt("Copy to clipboard: Ctrl+C, Enter", "¯\\_(ツ)_/¯"); })();
