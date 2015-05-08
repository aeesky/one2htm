## OneNote to HTML server ##
One2htm is a Windows system-tray application that provides read-only web access to **Microsoft OneNote** notebooks. One2htm monitors open notebooks for changes and exports any changed pages as HTML files into a destination folder. If this folder is web-accessible (through a service such as [Dropbox](http://www.dropbox.com)), the pages can be viewed with any browser. The system is designed particularly for mobile users who want to read their OneNote pages on their smartphone, but it works just as well on a desktop browser.

### Other features ###
  * Mobile-friendly index pages are generated for navigating around notebooks and sections.
  * Embedded images are also exported (as PNG files).
  * Hyperlinks between pages are maintained.
  * A shortcut list of recently-edited pages is generated alongside the section index.

### Recommended usage ###
  1. Install [DropBox](http://www.dropbox.com/downloading?src=index).
  1. Download One2htm.exe and save it somewhere convenient (such as Program Files).
  1. When One2htm runs for the first time it will ask for a destination folder for the exported HTML files. Choose the \Public folder inside the Dropbox folder. The entire tree of notebooks, sections and pages will be created in that folder.
  1. The \Public folder will then contain a file **index.htm**. Find the public URL for that file by following [these instructions from Dropbox](http://wiki.dropbox.com/TipsAndTricks/HostWebsites). Bookmark this link on your phone.
As long as One2htm remains running in the background, any page changes will be available on the web within a minute.

### Shared notebooks ###
One2htm has no problem working with shared notebooks: it will monitor all notebooks active on the current machine, even if OneNote itself is not running.