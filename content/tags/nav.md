+++
date = "2016-10-01T00:44:53+05:30"
next = "/tags/section"
prev = "/tags/aside"
title = "nav"
toc = true
weight = 5

+++

<p>The HTML &lt;nav&gt; element (HTML Navigation Element) represents a section of a page that links to other pages or to parts within the page: a section with navigation links. </p>

<h3>Need for this tag</h3>

<p>Not all links of a document must be in a &lt;nav&gt; element, which is intended only for major block of navigation links; typically the &lt;footer&gt; element often has a list of links that don't need to be in a &lt;nav&gt; element.</p>

<p>A document may have several &lt;nav&gt; elements, for example, one for site navigation and one for intra-page navigation.</p>

<p>User agents, such as screen readers targeting disabled users, can use this element to determine whether to omit the initial rendering of this content. </p>

<p>Below are a few more examples of other areas of the site in which you might consider using the &lt;nav&gt; element. It is also important to note that while XHTML 2 <nl> element, this hasn’t been replicated in HTML 5 because navigation does not have to take list form, as we’ll see.</p>

-- Table of Contents
I would say definitely yes to that – it is primary navigation for that particularly content
Previous/next buttons (or pagination)
I would say yes to this because it is important to the overall structure and hierarchy of the blog/site
-- Search form
For me, a definite yes, but it is not mentioned in the spec. A search form is hugely important to the navigation of a site, particularly large sites which rely almost solely on their search engine.
--  Breadcrumbs
Again, I would say yes to this as well. Although breadcrumbs are not always necessary and can be used when not applicable, on large sites a breadcrumb trail can be an important navigation aid.

<h3>Advantages of this tag</h3>
<ol>
  <li>Will help in Search Engine Optimization(SEO) by following the HTML standards</li>
  <li>Provides semantic meaning to the HTML page</li>
</ol>

<h3>Working Example</h3>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

<h3>The difference between 	&lt;nav&gt; and &lt;menu&gt;</h3>

<p>If you aren’t aware there is another element that can confuse the issue in the HTML 5 specification – menu. I’ve noticed that some developers are using the &lt;menu&gt; element for navigation rather than the &lt;nav&gt; element. We thought it best to clarify that &lt;menu&gt; is to be used for a list of commands and is an interactive element and more likely to be used exclusively in Web Applications.</p>

<h3>References</h3>
https://developer.mozilla.org/en/docs/Web/HTML/Element/nav
<br>
http://html5doctor.com/nav-element/
