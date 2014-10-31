Front End Resources
========
List Of Best CSS Sites:

<pre><a href="http://www.quackit.com/css/tutorial/css_lists.cfm">Quackit CSS Tutorial</a></pre>
<p>This Link has the best resources to play with HTML and CSS</p>

<strong>ARIA:</strong>
<ul>
<li><pre><b>Pop up:-</b>
<i>aria-haspopup = “false”</i>
	To indicate that there is no pop up for the input.
<i>aria-haspopup = “true”</i>
	To indicate that there is a pop up for the input.</pre><hr></li>

<li><pre><b>Auto Complete:-</b>
<i>aria-autocomplete = “both”</i>

aria-autocomplete indicates whether user input completion suggestions are provided.
both: A list of choices appears and the currently selected suggestion also appears inline.<br/>
Auto Complete have the role of combo box.<br/>
<input type=”text” aria-autocomplete=”both” role=”combobox”></pre><hr></li>

<li><pre><b>Visuallyhidden class:-</b>
“Visuallyhidden” class was originally from HTML5Boilerplate. It assists the screen readers.<br/>
Ideal for the links. We can give additional information related to the links in visuallyhidden.

Example:- <span class=”visuallyhidden”>Navigate</span>

.visuallyhidden {
	width: 1px;
	height: 1px;
	clip: rect(1px, 1px, 1px, 1px);
	overflow: hidden;
position: absolute !important;
}</pre><hr></li>
<li><pre>
<b>Aria-label and Aria-labelledby:-</b>
<i>aria-label</i> can be used when providing a visible and / or tooltip is not the desired user experience. <br/>However, if the label text is visible on screen, you should use aria-labelledby instead of aria-label<br/>
<button class=”search” aria-label= “Auto Search”>search</button>
<button class=”search” aria-labelledby=”Auto Search”>Auto Search</button>

</pre><hr></li>
<li><pre>
<b>Aria-expanded:-</b>
aria-expanded sets or retrieves the expanded state of the element.
<i>Aria-expanded = “true”</i>
	The element is expanded
<i>aria-expanded = “false”</i>
	The element Is not expanded
</pre><hr></li>
</ul>
