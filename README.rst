Summary
----------

This repo stores the xml code for adding syntax highlighting for languages not supported by default by the text editor Notepad++.

To add one of these, open the .xml file (in Notepad++, right?!), and then open the userDefineLang.xml, and add the new block of xml code, and restart Notepad++.  It should then appear in the bottom section of the Language menu in Notepad++.  You can customize the syntax highlighting via Notepad++'s ``View > User-Defined Dialogue...`` menu option.

If you have no custom syntaxes added yet, you might have to create the file? If so it would look like this::

	<NotepadPlus>
		<UserLang name="AHK Autohotkey" ext="ahk">
			...
		</UserLang>
	</NotepadPlus>
	
Languages
-----------

INI_and_CFG.xml :
	Simple highlighting for the .ini format that Windows created (or something like that...).  Also works for .cfg files.  Format is used by various libraries, such as Python's ConfigParser.
	
webbotlib_g8.xml :
	Highlighting for the xml-formatted robot gait data used by WebbotLib's GaitDesigner.
	
autohotkey_ahk.xml :
	Highlighting of most of the syntax for AutoHotkey.
	
msub.xml :
	Highlighting for parallel code submission syntax (msub, qsub, ...?).

