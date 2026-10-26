# Computer-grammar-practice
## content
1. [HTML](#HTML)
   1. [link](#Links)
   2. [image](#image)
   3. [images as link](#images-as-link)
   4. [Basic table](#basic-table)
2. [CSS](#CSS)
   1. [introduce CSS](#introduce)
   2. [classes and IDs](#class-and-id)
   3. [advanced tables](#advanced-tables)

<h2 id="HTML">HTML</h2>
<h3 id="Links"> 8/21/2026<br/>Links</h3>
<b>For example:</b><br/>
&lt;a href="http://www.google.com" target="_blank"&gt;look it up on Google &lt;/a&gt;<br/>
<a href="http://www.google.com" target="_blank">look it up on Google </a>
<p> Have a target can open up a new window. If you don't have a target, it can't open.</p>
<h3 id="image">8/27/2026<br>Image </h3>
<ol>
  <li>Have two ways</li>
  <li> copy the search webites. (Not recommended.)<br>
    <b>For example:</b><br/>
    &lt;img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIxe9mQdxfJWw1RDXb8wquk4OQdG008PypBJYicEcYfA&s=10" alt="cat" width="100" /&gt;<br/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIxe9mQdxfJWw1RDXb8wquk4OQdG008PypBJYicEcYfA&s=10" alt="cat" width="100" />
  </li>
  <li>To place an image on our web page.<br/>
    <b>For example:</b><br/>
    &lt;img src="images/University.png" alt="University" width="100" /&gt;<br/>
    <img src="images/University.png" alt="University" width="100" />
  </li>
</ol>
<h3 id="images-as-link">9/2/2026<br/>Images as link</h3>
<p>That can open websites(What you set up) in the pictures.(This is have "target") </p>
&lt;a href="http://www.google.com" target="_blank"&gt;<br/>
&lt;img src="images/cat.jpeg" alt="cat" width="100"/&gt;<br/>
&lt;/a&gt;<br/>
<a href="http://www.google.com" target="_blank">
<img src="images/cat.jpeg" alt="cat" width="100"/>
</a>
<h3 id="basic-table">9/4/2026<br/>Basic table</h3>
<ol>
<li><p>This is one row</p> 
  <table>
    <tr>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </table>
  &lt;table&gt;<br/>
  &emsp;&lt;tr&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&lt;/tr&gt;<br/>
  &lt;/table&gt;
</li>
<li>
    <p>This is one column</p>
  <table>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
      <tr>
        <td></td>
      </tr>
    </table>
  &lt;table><br/>
  &emsp;&lt;tr&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&lt;/tr&gt;<br/>
  &emsp;&lt;tr&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&lt;/tr&gt;<br/>
  &emsp;&lt;tr&gt;<br/>
  &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
  &emsp;&lt;/tr&gt;<br/>
  &lt;/table&gt;<br/>
  </li>
  <li>
    <p>Add boredr:browsers will display the table with vertical and horizontal borders around each cell. This makes
the table is a bit easier to view.<br>
   <b>Like this:</b></p>
    <table boredr="1">
    <tr>
      <td></td>
      <td></td>
    </tr>
     <tr>
      <td></td>
      <td></td>
    </tr>
       <tr>
      <td></td>
      <td></td>
    </tr>
    </table>
    &lt;table boredr="1"&gt;<br/>
    &emsp;&lt;tr&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&lt;/tr&gt;<br/>
    &emsp;&lt;tr&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&lt;/tr&gt;<br/>
    &emsp;&lt;tr&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&emsp;&lt;td&gt;&lt;/td&gt;<br/>
    &emsp;&lt;/tr&gt;<br/>
    &lt;/table&gt;<br/>
  </li>
</ol>
<h2 id="CSS">Into CSS</h2>
<h3 id="introduce">What is CSS</h3>

[Detailed down to README2.md](README2.md)

<h3 id="class-and-id">9/11/1026<br/>CSS Classes and ID's</h3>
<ol>
   <li>Styling declarations for IDs begin with the pound <b>sign(#)</b> and for classes with a <b>period(.)</b>. The id and class attribute, respectively, are added to page elements.</li>
   <li>IDs can be applied to one and only one element in a web document. </li>
   <li>Classes can be applied to an unlimited number of elements, even different types of elements on the same page. </li>
   <li>If conflicting styles from an ID and class are applied to the same element, the ID will outrank the class in the c</li>
   <li>the &lt;span&gt; element does nothing on its own. Only once we associate it with a CSS class will the text inside the &lt;span&gt; be affected.</li>
</ol>
<h3 id="advanced-tables">9/17/2026<br/>Advanced Tables </h3>
<ol>
   <li> 
   Spanning Columns<br/>The value placed in the colspan attribute informs the browser how many columns combine into a single data cell. <br/>
   Example:<br/>
<table border="1">
 <tr>
  <td colspan="3">Row 1 Col 1-3</td>
 </tr>
 <tr>
  <td>Row 2 Col 1</td>
  <td>Row 2 Col 2</td>
  <td>Row 2 Col 3</td>
 </tr>
 <tr>
  <td>Row 3 Col 1</td>
  <td>Row 3 Col 2</td>
  <td>Row 3 Col 3</td>
 </tr>
</table>
&lt;table border="1"&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td colspan="3"&gt;Row 1 Col 1-3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 2 Col 1&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 2 Col 2&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 2 Col 3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 3 Col 1&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 3 Col 2&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 3 Col 3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&lt;/table&gt;<br/>
   </li>
   <li>
      Spanning Rows<br/>The rowspan attribute works the same way by informing the browser how many rows to combine into a single cell.<br/>
      Example:<br/>
<table border="1">
 <tr>
  <td rowspan="3">Col 1 Row 1-3</td>
  <td>Row 1 Col 2</td>
  <td>Row 1 Col 3</td>
</tr>
<tr>
  <td>Row 2 Col 2</td>
  <td>Row 2 Col 3</td>
</tr>
<tr>
  <td>Row 3 Col 2</td>
  <td>Row 3 Col 3</td>
</tr>
</table> 
&lt;table border="1"&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td rowspan="3"&gt;Col 1 Row 1-3&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 1 Col 2&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 1 Col 3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 2 Col 2&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 2 Col 3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&emsp;&lt;tr&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 3 Col 2&lt;/td&gt;<br/>
&emsp;&emsp;&lt;td&gt;Row 3 Col 3&lt;/td&gt;<br/>
&emsp;&lt;/tr&gt;<br/>
&lt;/table&gt;     
   </li>
   <li>
      To add a caption to the table, we use the <caption> element immediately after the opening <table> tag. The text enclosed within the <caption> element will be displayed above the table and centered.
   </li>
   <li>
      Many other elements can be placed inside table cells, including paragraphs, links, images, lists, and even other tables.<br/>
      <b>Like:</b><br/>
<table border="1">
 <tr>
  <td>
   <p><a href="page2.html">Go to Next Page</a></p>
  </td>
  <td>
   <img src="images/cat.jpeg" alt="cat" width="100"/>
  </td>
 </tr>
 <tr>
  <td>
   <ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
   </ol>
  </td>
  <td>
   <table border="1">
    <tr>
     <td>R1C1</td><td>R1C2</td>
    </tr>
    <tr>
     <td>R2C1</td><td>R2C2</td>
    </tr>
   </table>
  </td>
 </tr>
</table>
   </li>
   <li><br/>
      <table>
         <tr>
            <th colspan="2" align="center">Table Styling</th>
         </tr>
         <tr>
            <th>Style</th>
            <th>Description</th>
         </tr>
         <tr>
            <td>width</td>
            <td>width of element</td>
         </tr>
         <tr>
            <td>background-color</td>
            <td>background color of element</td>
         </tr>
         <tr>
            <td>color</td>
            <td>color of text in element</td>
         </tr>
         <tr>
            <td>text-align</td>
            <td>horizontal text alignment of element</td>
         </tr>
         <tr>
            <td>border</td>
            <td>border thickness and style of element</td>
         </tr>
         <tr>
            <td>padding</td>
            <td>padding (white space around content) of element</td>
         </tr>
   </li>
</ol>
