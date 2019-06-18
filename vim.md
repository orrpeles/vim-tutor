
# Table of Contents

1.  [Vimtutor for the impatient](#org6db80fb)
    1.  [Lesson 1](#orgfa02809)
        1.  [Moving the cursor](#orgca060dd)
    2.  [Lesson 2](#org44336aa)
        1.  [Deletion commands](#orgc464b4e)
    3.  [Lesson 3](#org4b1ea2c)
    4.  [Lesson 4](#orgdede020)
        1.  [Cursor location and File status](#orgc8092bc)
        2.  [Search commad](#orgb2a8d95)
        3.  [Matching Parentheses search and substitute command](#org478f1f4)
    5.  [Lesson 5](#orgb5ff305)
    6.  [Lesson 6](#org86415b7)
    7.  [Lesson 7](#org462c44a)
        1.  [Getting help](#orgae58d40)



<a id="org6db80fb"></a>

# Vimtutor for the impatient


<a id="orgfa02809"></a>

## Lesson 1


<a id="orgca060dd"></a>

### Moving the cursor

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">h</td>
<td class="org-left">Move to left</td>
</tr>


<tr>
<td class="org-left">l</td>
<td class="org-left">Move to right</td>
</tr>


<tr>
<td class="org-left">j</td>
<td class="org-left">Move down</td>
</tr>


<tr>
<td class="org-left">k</td>
<td class="org-left">Move up</td>
</tr>
</tbody>
</table>


<a id="org44336aa"></a>

## Lesson 2


<a id="orgc464b4e"></a>

### Deletion commands

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">dw</td>
<td class="org-left">Delete the letters from the current word, until end</td>
</tr>


<tr>
<td class="org-left">d$</td>
<td class="org-left">Delete to the end of the line</td>
</tr>


<tr>
<td class="org-left">dd</td>
<td class="org-left">Delete a line</td>
</tr>


<tr>
<td class="org-left">u</td>
<td class="org-left">Undo the last command</td>
</tr>


<tr>
<td class="org-left">U</td>
<td class="org-left">Undo the whole line</td>
</tr>


<tr>
<td class="org-left">Ctrl-R</td>
<td class="org-left">Undo the undo's</td>
</tr>
</tbody>
</table>


<a id="org4b1ea2c"></a>

## Lesson 3

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">p</td>
<td class="org-left">Put the 'text' below the cursor</td>
</tr>


<tr>
<td class="org-left">r</td>
<td class="org-left">Replace the character under the cursor</td>
</tr>


<tr>
<td class="org-left">ce</td>
<td class="org-left">change till the end of the word</td>
</tr>


<tr>
<td class="org-left">c$</td>
<td class="org-left">change till the end of the line</td>
</tr>
</tbody>
</table>


<a id="orgdede020"></a>

## Lesson 4


<a id="orgc8092bc"></a>

### Cursor location and File status

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">Ctrl + g</td>
<td class="org-left">Show file status</td>
</tr>


<tr>
<td class="org-left">gg</td>
<td class="org-left">Goto the top of the file</td>
</tr>


<tr>
<td class="org-left">G</td>
<td class="org-left">Goto the end of the file</td>
</tr>


<tr>
<td class="org-left">{linenumer}G</td>
<td class="org-left">Goto the specified line number</td>
</tr>
</tbody>
</table>


<a id="orgb2a8d95"></a>

### Search commad

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">/</td>
<td class="org-left">Forward seach</td>
</tr>


<tr>
<td class="org-left">?</td>
<td class="org-left">Backward search</td>
</tr>


<tr>
<td class="org-left">n</td>
<td class="org-left">Goto the next instance of the matched phrase</td>
</tr>


<tr>
<td class="org-left">N</td>
<td class="org-left">Goto to the next instance(opposite direction)</td>
</tr>
</tbody>
</table>


<a id="org478f1f4"></a>

### Matching Parentheses search and substitute command

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">%</td>
<td class="org-left">Find the matching ), ], }</td>
</tr>


<tr>
<td class="org-left">:s/old/new</td>
<td class="org-left">substitue the old word with the new word on the line</td>
</tr>


<tr>
<td class="org-left">:s/old/new/g</td>
<td class="org-left">Globally make this change on the line</td>
</tr>
</tbody>
</table>


<a id="orgb5ff305"></a>

## Lesson 5

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">:! {shell command}</td>
<td class="org-left">Execute shell command</td>
</tr>


<tr>
<td class="org-left">:w TEST</td>
<td class="org-left">Write the current buffer to a file named 'TEST'</td>
</tr>


<tr>
<td class="org-left">:r TEST</td>
<td class="org-left">Insert content of file 'TEST' below the cursor</td>
</tr>
</tbody>
</table>


<a id="org86415b7"></a>

## Lesson 6

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">a</td>
<td class="org-left">Append the text after the cursor</td>
</tr>


<tr>
<td class="org-left">A</td>
<td class="org-left">Append the text at the end of line</td>
</tr>


<tr>
<td class="org-left">y</td>
<td class="org-left">Copy(yank)</td>
</tr>


<tr>
<td class="org-left">p</td>
<td class="org-left">Paste(put)</td>
</tr>


<tr>
<td class="org-left">o</td>
<td class="org-left">Open a line below the cursor</td>
</tr>


<tr>
<td class="org-left">O</td>
<td class="org-left">Open a line above the cursor</td>
</tr>


<tr>
<td class="org-left">R</td>
<td class="org-left">Replace more than one character</td>
</tr>
</tbody>
</table>


<a id="org462c44a"></a>

## Lesson 7


<a id="orgae58d40"></a>

### Getting help

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Command</th>
<th scope="col" class="org-left">Description</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">:help</td>
<td class="org-left">Access help window</td>
</tr>


<tr>
<td class="org-left">:help {helpterm}</td>
<td class="org-left">Search for helpterm</td>
</tr>


<tr>
<td class="org-left">:help {helpterm} Ctrl + d</td>
<td class="org-left">Show related helpterms</td>
</tr>


<tr>
<td class="org-left">Ctrl + w Ctrl + w</td>
<td class="org-left">Jump from one window to another</td>
</tr>
</tbody>
</table>

