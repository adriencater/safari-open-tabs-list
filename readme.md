# AppleScript that make a list of open safari windows and tabs

Because I have a lot of tabs open, and sometimes would like to save them.


## TO-DO

- save a html directly from the script rather than going through TextEdit.
	- https://stackoverflow.com/questions/3780985/how-do-i-write-to-a-text-file-using-applescript
	- https://stackoverflow.com/questions/14532518/applescript-save-as-html-in-textedit

- format the HTML as bookmarks.html
	- https://kb.mozillazine.org/Bookmarks.html
	- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl
	- https://support.mozilla.org/en-US/questions/1319392

- schedule automatic datestamped file creation

```

	<DL>
		<DT><H3>Folder Name 1</H3></DT>
		<DL>
			<DT><A HREF="https://support.mozilla.org/en-US/products/firefox">Help and Tutorials</A></DT>
			<DT><A HREF="https://support.mozilla.org/en-US/kb/customize-firefox-controls-buttons-and-toolbars">Customize Firefox</A></DT>
		</DL>
		<DT><H3>Folder Name B</H3></DT>
		<DL>
			<DT><A HREF="https://www.mozilla.org/en-US/contribute/">Get Involved</A></DT>
			<DT><A HREF="https://www.mozilla.org/en-US/about/">About Us</A></DT>
		</DL>
	</DL>

```

### Research & references

https://apple.stackexchange.com/questions/206427/can-you-see-a-list-of-all-open-tabs-in-safari

https://code.tutsplus.com/generate-a-list-of-open-safari-tabs-with-applescript--mac-30564t
