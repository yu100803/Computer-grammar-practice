<h1>About CSS</h1>
<h3>What is CSS</h3>
<ol>
  <li>CSS ("Cascading Style Sheets") determines how the elements in our XHTML documents are displayed and formatted.</li>
  <li>By using CSS, we separate the content of a web page from the presentation (format and styling) of that content.</li>
  <li>CSS enables us to make all pages of our website look similar and consistent.</li>
  <li>The power of CSS is that it allows us to make site-wide formatting changes by making edits to a single file.</li>
</ol>
<h3>Three ways to use CSS</h3>
<ol>
  <li>Inline Style - CSS code is placed directly into an XHTML element within the &lt;body&gt; section of a web page.<br/>
  For example:<br/>&lt;h2 style="color:red;"&gt;CAUTION: Icy Road Conditions&lt;/h2&gt;</li>
  <li>Internal Style Sheet - CSS code is placed into a separate, dedicated area within the &lt;head&gt; section of a web page.<br/>
  For example:<br/>
  &lt;head&gt;<br/>
...<br/>
&lt;style&gt;<br/>
h2 {color:red;}<br/>
&lt;/style&gt;<br/>
&lt;/head&gt;<br/>
&lt;body&gt;<br/>
&lt;h2&gt;CAUTION: Icy Road Conditions&lt;/h2&gt;<br/>
&lt;h2&gt;Please Slow Down!&lt;/h2&gt;<br/>
&lt;/body&gt;
</li>
  <li>External Style Sheet - CSS code is placed into a separate computer file and then linked to a web page.
  For example<br/>
  style.css (separate file):<br/>h2{color:red;}<br/>
  &lt;head&gt;<br/>
&lt;link rel="stylesheet" type="text/css" href="style.css" /&gt;<br/>
...<br/> 
&lt;/head&gt;<br/>
&lt;body&gt;<br/>
&lt;h2&gt;CAUTION: Icy Road Conditions&lt;/h2&gt;<br/>
&lt;h2&gt;Please Slow Down!&lt;/h2&gt;<br/>
&lt;/body&gt;
  </li>
</ol>
<h2>CSS Text Properties</h2>
<table>
  <tr>
    <th>Property</th>
    <th>Some Possible Values</th>
  </tr>
  <tr>
    <td>text-align:</td>
    <td>center, left, right, justify</td>
  </tr>
  <tr>
    <td>text-decoration: </td>
    <td>underline, line-through, blink</td>
  </tr>
  <tr>
    <td>color: </td>
    <td>blue, green, yellow,#3297a8,etc.</td>
  </tr>
  <tr>
    <td>font-family:</td>
    <td>Arial, Verdana, "Times New Roman"</td>
  </tr>
  <tr>
    <td>font-size: </td>
    <td>large, 120%, 20px (pixels)</td>
  </tr>
  <tr>
    <td>font-weight: </td>
    <td>bold, normal</td>
  </tr>
  <tr>
    <td>font-style: </td>
    <td>italic, normal</td>
  </tr>
</table>
