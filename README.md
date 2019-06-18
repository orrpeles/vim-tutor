
# Table of Contents

1.  [Vimtutor for the impatient](#org18c98ad)
    1.  [Lesson 1](#org6567ed3)
        1.  [Moving the cursor](#orgbb5d781)
    2.  [Lesson 2](#org3401029)
        1.  [Deletion commands](#orge6b3f41)
        2.  [Operator and motion](#org05c2260)
    3.  [Lesson 3](#org4baffd6)
    4.  [Lesson 4](#orgd53e1a6)
        1.  [Cursor location and File status](#orgddb413e)
        2.  [Search commad](#org1b41994)
        3.  [Matching Parentheses search and substitute command](#org4e5ad05)
    5.  [Lesson 5](#orgbdbfaab)
    6.  [Lesson 6](#orgb00d06d)
    7.  [Lesson 7](#org399eb30)
        1.  [Getting help](#org1476780)



<a id="org18c98ad"></a>

# Vimtutor for the impatient


<a id="org6567ed3"></a>

## Lesson 1


<a id="orgbb5d781"></a>

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


<a id="org3401029"></a>

## Lesson 2


<a id="orge6b3f41"></a>

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
<td class="org-left">Delete a word</td>
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


<a id="org05c2260"></a>

### Operator and motion


<a id="org4baffd6"></a>

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


<a id="orgd53e1a6"></a>

## Lesson 4


<a id="orgddb413e"></a>

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


<a id="org1b41994"></a>

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


<tr>
<td class="org-left">Ctrl + o</td>
<td class="org-left">Goto tho where you seached initially</td>
</tr>
</tbody>
</table>


<a id="org4e5ad05"></a>

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
<td class="org-left">substitue the old word with the new word</td>
</tr>


<tr>
<td class="org-left">:s/old/new/g</td>
<td class="org-left">Globally make this change</td>
</tr>
</tbody>
</table>


<a id="orgbdbfaab"></a>

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
<td class="org-left">Save the current file under the name 'TEST'</td>
</tr>


<tr>
<td class="org-left">:r TEST</td>
<td class="org-left">Retrieve the content of 'TEST' and paste below the cursor</td>
</tr>
</tbody>
</table>


<a id="orgb00d06d"></a>

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


<a id="org399eb30"></a>

## Lesson 7


<a id="org1476780"></a>

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
<td class="org-left">Show related helpterms and use TAB for autocompletion</td>
</tr>


<tr>
<td class="org-left">Ctrl + w Ctrl + w</td>
<td class="org-left">Jump from one window to another</td>
</tr>
</tbody>
</table>

