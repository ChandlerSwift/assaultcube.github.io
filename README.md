The "htdocs" folder contains all of the files on the 
main-part of the AssaultCube website, except the following:

	./schemas		(link)
	./transformations	(link)
	./$_DATA_STORAGE	(folder/contents)

The "dollar underscore" folders and its contents aren't kept in
this repository, as their contents may change at any time without
warning and aren't essential to the running of the website.

This folder does/will not contain (at least, for now):
	* The forum
	* The wiki
	* The masterserver

Any AssaultCube documentation should be added to ./htdocs/docs 
from now on. Upon any AC releases, simply copy/paste 
the ./htdocs/docs folder into the release. No changes necessary.


## Other folders/files in THIS directory:

 * "INFO.txt" - Information about the "ac_website" repository (this file).
 * "DATASTORAGE_HEADER.html" - This file will update the parts of the webpage
   found at http://assault.cubers.net/$_DATA_STORAGE that aren't automatically
   generated by APACHE. On the actual site, this file is normally named "HEADER.html".
 * "DOCS_TEMPLATE.html" - This file should be used as a template for any new
    documentation webpage. Read this file for more info.

AC Developers:
   If you have NEVER changed ANY files within this repository before,
   then PLEASE ensure you've asked flowtron or RandumKiwi about
   how things work, before you change files for the first time.

   DO NOT TOUCH ANYTHING UNTIL YOU HAVE!

   
## LIST OF FILES TO CHANGE UPON NEW RELEASES:

 * Update ./htdocs/SSI-HTML/download_box.html
 * Update ./htdocs/download.html
 * Update "docswarning" with the location of the new versions
   current docfiles at ./htdocs/SSI-HTML/docs/docswarn.html
 * Check/Update ./htdocs/index.html if any AC specifications have changed.
 * Add new ./htdocs/uninstallnotes webpage.
 * Add new ./htdocs/releasenotes webpage.

