HTML Semantic Elements :

Semantic elements = elements with a meaning.

What are Semantic Elements?
A semantic element clearly describes its meaning to both the browser and the developer.

Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

Examples of semantic elements: <img>, <table>, and <article> - Clearly defines its content.

Semantic Elements in HTML
Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.

In HTML there are several semantic elements that can be used to define different parts of a web page:  

<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>

HTML <section> Element
The <section> element defines a section in a document.

According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading."

Examples of where a <section> element can be used:

Chapters
Introduction
News items
Contact information
A web page could normally be split into sections for introduction, content, and contact information.

HTML <article> Element
The <article> element specifies independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

Examples of where the <article> element can be used:

Forum posts
Blog posts
User comments
Product cards
Newspaper articles

Nesting <article> in <section> or Vice Versa?
The <article> element specifies independent, self-contained content.

The <section> element defines a section in a document.

Can we use the definitions to decide how to nest those elements? No, we cannot!

So, you will find HTML pages with <section> elements containing <article> elements, and <article> elements containing <section> elements.

HTML <footer> Element
The <footer> element defines a footer for a document or section.

A <footer> element typically contains:

authorship information
copyright information
contact information
sitemap
back to top links
related documents
You can have several <footer> elements in one document.

HTML <nav> Element
The <nav> element defines a set of navigation links.

Notice that NOT all links of a document should be inside a <nav> element. The <nav> element is intended only for major blocks of navigation links.

HTML <aside> Element
The <aside> element defines some content aside from the content it is placed in (like a sidebar).

The <aside> content should be indirectly related to the surrounding content.

HTML <figure> and <figcaption> Elements
The <figure> tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

The <figcaption> tag defines a caption for a <figure> element. The <figcaption> element can be placed as the first or as the last child of a <figure> element.

The <img> element defines the actual image/illustration. 

Why Semantic Elements?
According to the W3C: "A semantic Web allows data to be shared and reused across applications, enterprises, and communities."