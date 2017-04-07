# Validate Your HTML Markup

## Motivation

To educate the world about the benefits of making sure their HTML/etc. markup
is valid according to the web standards.

## What is valid HTML markup?

Most web browsers will accept various variations in the HTML markup language,
but often will not know exactly what to do unless the markup is well-formed
and strictly abides by the WWW standards. To make it easier for browsers,
for other HTML consumers and processors, and for general good measure, one
should make sure the HTML **validates** and thus is **valid**.

## Why validate?

* By validating your pages you make sure the structure of the document is
acceptable to standards-compliant browsers.
* When you deviate from the
standard, you don't know how the browser is going to react.
* Saying that "I don't know if my site is standards compliant or not, but
it looks good in all browsers." (or just in one browser and one platform
on which it was tested) is not a good idea.
* The browsers may not display
this page correctly in future versions, or a new browser may do
things differently.
* (For instance, when MSIE 5.0 came, it was more standards-compliant than MSIE 4.x and as a result many sites that worked with IE before became broken. This happened in the release of MSIE 6.0, and in Windows XP Service Pack 2, as well.)
* The browser has a tough job as it is, so you shouldn't make it tougher by sending it mal-formed input.

### Caveats

* Standards-compliance is not a panacea.
* Even if all the output from the site is standards-compliant it doesn't mean it will display correctly.
* This is either because of bugs in the browsers, or because you haven't done the right thing.
* So, it is important to test the pages in as many browsers as possible, in
addition to validating them.

## How to validate?

A [DuckDuckGo search](https://duckduckgo.com/?q=html+validator&ia=web) for
“html validator” as well as a
[Google search](https://encrypted.google.com/search?hl=en&q=html%20validator)
will yield many results. Note that you should first pick up a verion of the
HTML or XHTML standards (such as [HTML5](https://en.wikipedia.org/wiki/HTML5)
or [XHTML 1.1](https://www.w3.org/TR/xhtml11/) and use the correct
[Doctype](https://en.wikipedia.org/wiki/Document_type_declaration) to indicate
that this is the case. Different pages may be under different versions of
the standard.
