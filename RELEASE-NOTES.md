## Version 3.0.4: 

* Removed popup menu for the browser action; now, clicking on 
  the Tranquility icon will make the page readable. For the 
  other actions provided through the popup menu, users will have 
  to go to the options page or use the Read Later button after 
  running tranquility.

* Added a few "preset" configurations (color schemes and font colors) 
  rather than having to customize each option manually. 
  This is experimental at this time; will explore the option of 
  allowing users to import a configuration file for this in the future.

* Changed the background page to "about:blank" (instead of mozilla.org) 
  when loading offline pages from the options window.

* Minor bug fix to remove the progress bar which was not being removed 
  in some corner cases.

* Bug fix to correctly load original page when toggling Tranquility mode 
  for an offline page.

* Bug fix to handle loading mixed security content pages correctly

* Bug fix to handle pre-formatted pages correctly 

--------------------------------

## Version 3.0.1:

* Tranquility Reader 3.0.1 has been rewritten using WebExtensions APIs

* Ability to export/import offline content (please be sure to export 
  offline content from version 2.0 and manually import into version 3.0.1)

* Reduced set of customization options; Display font name will have 
  to be typed in manually (limitation of WebExtensions APIs)

* Removed support for background image and wikipedia/wiktionary 
  search facility

* No keyboard shortcut (very limited options available through 
  WebExtensions APIs - waiting for more customization capabilities)

* Several minor bug fixes that were put off until this version

Please note that due to the extensive changes that were made, there 
may be regression in the code and past bugs that were fixed may reappear. 
Please leave your comments or send feedback to the support email 
address so that these bugs can be addressed. 