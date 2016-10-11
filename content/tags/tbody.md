+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/comments"
prev = "/tags/abbreviation"
title = "tbody"
toc = true
weight = 5

+++

<h3>Standard Definition</h3>

<h3>Need for this tag</h3>

<h3>Disadvantages of this tag</h3>

<h3>Advantages of this tag</h3>

you can actually code <thead>, <tfoot>, and <tbody> out of order and they will appear in the right place on the table. While obscure, I have taken advantage of this before
The thead, tbody, and tfoot elements in HTML are used to group table rows into logical sections based on their content. There are two main reasons you'd want to do this:

They allow you to add semantics to your table
allow you to style the head and the foot of the table without introducing redundant classes/ids
To allow the body to be scrolled independently of the header and/or
footer
To make it easier to apply different style rules to the different sections of the table.

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
