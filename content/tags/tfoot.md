+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/comments"
prev = "/tags/abbreviation"
title = "tfoot"
toc = true
weight = 5

+++

<h3>Standard Definition</h3>

<h3>Need for this tag</h3>


<h3>Advantages of this tag</h3>

<ul>
  <li>The <span class='tag-span'>&lt;thead&gt;</span>, <span class='tag-span'>&lt;tbody&gt;</span> ,<span class='tag-span'>&lt;tfoot&gt;</span> elements in HTML are used to group table rows into logical sections based on their content. There are two main reasons you'd want to do this:

  <ol>
    <li>They allow you to add semantics to your table.
    <li>They allow you to style the head and the foot of the table without introducing redundant classes/ids</li>
  </ol>

  <li>This division enables user agents to support scrolling of table bodies independently of the table head and foot.</li>

  <li> When long tables are printed, the table head and foot information may be repeated on each page that contains table data.</li>

</ul>

{{% notice note %}}
  You can actually code <span class='tag-span'>&lt;thead&gt;</span>, <span class='tag-span'> &lt;tfoot&gt;</span>, <span class='tag-span'>&lt;tbody&gt;</span> out of order and they will appear in the right place on the table. While obscure, this is one of advantage of table related semantics tag.
{{% /notice %}}

{{% notice tip %}}
  Since order of <span class='tag-span'>&lt;thead&gt;</span>, <span class='tag-span'> &lt;tfoot&gt;</span>, <span class='tag-span'>&lt;tbody&gt;</span> doesn't matter, the idea of putting <span class='tag-span'>&lt;tfoot&gt;</span> before
  <span class='tag-span'>&lt;tbody&gt;</span> is encouraged so that summary (footer) information can be rendered while a large data table is still downloading
{{% /notice %}}

<h3>Working Example</h3>

    <table>
      <thead>
        <tr>
          <th>Season</th>
          <th>Goals</th>
          <th>Assists</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>2009-2010</th>
          <td>25</td>
          <td>43</td>
        </tr>
        <tr>
          <th>2011-2012</th>
          <td>40</td>
          <td>20</td>
        </tr>
      </tbody>
    </table>

<h3>References</h3>

<h3>Point of Contact</h3>
