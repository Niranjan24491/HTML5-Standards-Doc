+++
date = "2016-10-01T00:45:05+05:30"
next = "/tags/comments"
prev = "/tags/abbreviation"
title = "address"
toc = true
weight = 5

+++

The HTML <address> tag is used for indicating an address, usually related to authorship of the current document, or a section of the document.
If the tag applies to the body element, then it applies to the document as a whole.

<h3>Need for this tag</h3>
The <address> tag must not be used to represent arbitrary addresses (e.g. postal addresses), unless those addresses are contact information for the section. To display postal addresses, simply use the <p> tag.
This element should not contain more information than the contact information, like a publication date (which belongs in a <time> element).
Typically an <address> element can be placed inside the <footer> element of the current section, if any.

<h3>Disadvantages of this tag</h3>
The <address> tag cannot contain <article>, <aside>, <nav>, <section>, <header>, <footer>, <hgroup>, <h1>-<h6> or other <address> elements.

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>
<address>
    You can contact author at <a href="http://www.somedomain.com/contact">www.somedomain.com</a>.<br>
    If you see any bugs, please <a href="mailto:webmaster@somedomain.com">contact webmaster</a>.<br>
    You may also want to visit us:<br>
    Mozilla Foundation<br>
    1981 Landings Drive<br>
    Building K<br>
    Mountain View, CA 94043-0801<br>
    USA
  </address>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/address
<br>
http://www.quackit.com/html_5/tags/html_address_tag.cfm

<h3>Point of Contact</h3>
Niranjan Thrineshwar <br>
nthrineshwar@deloitte.com <br>
9663770742
