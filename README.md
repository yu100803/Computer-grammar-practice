# Computer-grammar-practice
## content
1. [Jump to HTML ](#HTML)
   1. [link](#Links)
   2. [image](#image)
   3. [images as link](#images-as-link)
   4. [Basic table](#basic-table)
2. [Jump to CSS ](#CSS)
   1. [introduce CSS](#introduce)
   2. [classes and IDs](#class-and-id)

<h2 id="HTML">HTML</h2>
<h3 id="Links"> 8/21/2026<br/>Links</h3>
For example:<br/>
&lt;a href="http://www.google.com" target="_blank"&gt;look it up on Google &lt;/a&gt;<br/>
<a href="http://www.google.com" target="_blank">look it up on Google </a>
<p> Have a target can open up a new window. If you don't have a target, it can't open.</p>
<h3 id="image">8/27/2026<br>Image </h3>
<ol>
  <li>Have two ways</li>
  <li> copy the search webites. (Not recommended.)<br>
    For example:<br/>
    &lt;img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIxe9mQdxfJWw1RDXb8wquk4OQdG008PypBJYicEcYfA&s=10" alt="cat" width="100" /&gt;<br/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIxe9mQdxfJWw1RDXb8wquk4OQdG008PypBJYicEcYfA&s=10" alt="cat" width="100" />
  </li>
  <li>To place an image on our web page.<br/>
    For example:<br/>
    &lt;img src="images/University.png" alt="cat" width="100" /&gt;<br/>
    <img src="images/University.png" alt="cat" width="100" />
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
the table is a bit easier to view.<br>Like this:</p>
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
   <li>Styling declarations for IDs begin with the pound sign(#) and for classes with a period(.). The id and class attribute, respectively, are added to page elements.</li>
   <li>IDs can be applied to one and only one element in a web document. </li>
   <li>Classes can be applied to an unlimited number of elements, even different types of elements on the same page. </li>
   <li>If conflicting styles from an ID and class are applied to the same element, the ID will outrank the class in the c</li>
   <li>the &lt;span&gt; element does nothing on its own. Only once we associate it with a CSS class will the text inside the &lt;span&gt; be affected.</li>
</ol>
