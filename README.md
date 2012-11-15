<h1>jQuery Code Hinting and Autocompletion in Notepad++</h1>

This project consists of user-defined language files for the <a href="http://notepad-plus-plus.org/" target="_blank">Notepad++ source code editor</a> designed to add code hinting and autocompletion for jQuery methods.

<h2>Screenshots</h2>

<img src="http://www.jamesallardice.com/assets/images/posts/notepadplusplusjquery1.jpg" alt="jQuery autocompletion" />
<img src="http://www.jamesallardice.com/assets/images/posts/notepadplusplusjquery2.jpg" alt="jQuery code hinting" />

<h2>Installation</h2>

<ul>
<li>Download both <em>userDefineLang_jQuery.xml</em> and <em>jquery.xml</em></li>
<li>Locate your Notepad++ installation directory and open up <em>userDefineLang.xml</em></li>
<li>If the file is currently empty you don't have any user defined languages and you can simply replace the file with <em>userDefineLang_jQuery.xml</em> and rename it to <em>userDefineLang.xml</em></li>
<li>If the file already has user defined languages in it you will need to merge it with <em>userDefineLang_jQuery.xml</em>.
<ul>
<li>Copy the contents of <em>userDefineLang_jQuery.xml</em> and paste it at the bottom of the existing <em>userDefineLang.xml</em></li>
<li>Remove the superfluous `</NotepadPlus><NotepadPlus>` at the point at which you pasted in the new content</li>
<li>Save and close this file</li>
</ul>
</li>
<li>Open up the <em>plugins/APIs</em> directory and move the <em>jquery.xml</em> file into this location</li>
<li>Start up Notepad++. Select "Language" from the toolbar and then "jQuery" from the bottom
<ul>
<li>If "jQuery" does not appear in the list click on "View" followed by "User-Defined Dialogue..."</li>
<li>In the User-Defined Dialogue click "Import" and select the <em>userDefineLang.xml</em> file</li>
<li>Close the dialogue and restart the application. jQuery should now appear in the Language menu</li>
</ul>
</li>