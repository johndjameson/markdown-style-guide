Markdown Style Guide
====================

> Markdown is not a replacement for HTML, or even close to it. Its syntax is
> very small, corresponding only to a very small subset of HTML tags. The idea
> is *not* to create a syntax that makes it easier to insert HTML tags. In my
> opinion, HTML tags are already easy to insert. The idea for Markdown is to
> make it easy to read, write, and edit prose. HTML is a *publishing* format;
> Markdown is a *writing* format.

— [Markdown Syntax Documentation][markdown-syntax]


Document Structure
------------------

Markdown documents should follow the following structure:

1. YAML front matter
2. Content
3. Image label definitions
4. Link label definitions


Headings
--------

-  Underline `h1` elements using equals signs `=`
-  Underline `h2` elements using hyphens `-`
-  Use two blank new lines to separate `h2` elements from earlier content
-  Use multiple hashes `#` for `h3` through `h6`
-  Use a single blank new line after all headings

```
This is an h1
=============


This is an h2
-------------

### h3

#### h4

##### h5

###### h6
```


Lists
-----

-  Use hyphens `-` for unordered list items
   -  Insert two spaces following hyphens
-  Use numbers followed by periods `1.` for ordered list items
   -  Insert a single space following periods
-  Don't wrap text in list items

```
-  This is an unordered list item
  -  This is a nested unordered list item
-  This is an unordered list item
  1. This is an ordered list item
```


Links
-----

-  Label all links at the bottom of the Markdown file.
-  Use only lowercase letters when labeling links.
-  Use hyphens to separate words in a link label.

<!-- The following code block is indented to prevent link label definitions from being parsed literally. Use the backtick syntax for all other code blocks. -->

	This paragraph contains a link to a CSS-Tricks [blog post][csstricks-prefill-forms].

	[csstricks-prefill-forms]: http://css-tricks.com/prefill-forms-dev/


Special Characters
------------------




HTML
----

> For any markup that is not covered by Markdown's syntax, you simply use HTML
> itself. There's no need to preface it or delimit it to indicate that you're
> switching from Markdown to HTML; you just use the tags.

— [Markdown Syntax Documentation][markdown-syntax]

[markdown-syntax]: http://daringfireball.net/projects/markdown/syntax
