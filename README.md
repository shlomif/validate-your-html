# Validate Your HTML Markup

## Motivation

To educate the world about the benefits of making sure their markup of
[HTML](http://en.wikipedia.org/wiki/HTML) and other web and non-web languages
is valid according to the web standards.

## What is valid HTML markup?

Most web browsers will accept various variations in the HTML markup language,
but often will not know exactly what to do, unless the markup is well-formed
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
* (For instance, when [MSIE](https://en.wikipedia.org/wiki/Internet_Explorer) 5.0 came, it was more standards-compliant than MSIE 4.x and as a result many sites that worked with IE before became broken. This happened in the release of MSIE 6.0, and in Windows XP Service Pack 2, as well.)
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
will yield many results. Note that you should first choose a version of the
HTML or XHTML standards (such as [HTML5](https://en.wikipedia.org/wiki/HTML5)
or [XHTML 1.1](https://www.w3.org/TR/xhtml11/)) and use their correct
[Doctype](https://en.wikipedia.org/wiki/Document_type_declaration) to indicate
that you are using them. Different HTML pages (even ones on the same site)
may adhere to different versions of the standards, and validate accordingly,
as long as they specify the appropriate doctypes.

### Some prominent validators

* [The W3C validator](https://validator.w3.org/)
* [tidyp](http://tidyp.com/) - a library and a command-line program for validating and fixing HTML. It is recommended to run it with all warnings displayed.

## The more general case: linting and validating

WWW Markup Validation is a specific case of
[“linting”](http://stackoverflow.com/questions/8503559/what-is-linting) where
one runs a program to make sure bad idioms are not present in one’s code or
markup. There are links to more linters and checkers below.

## Links

* [Coding Horror: “HTML Validation: Does It Matter?”](https://blog.codinghorror.com/html-validation-does-it-matter/)
* [Perl Elements to Avoid](http://perl-begin.org/tutorials/bad-elements/) - mentions other good practices.
* [tidyall](https://metacpan.org/pod/distribution/Code-TidyAll/bin/tidyall) - an all-in-one linter, validator and tidier.
* [check-all-the-things](http://bonedaddy.net/pabs3/log/2016/07/04/check-all-the-things/) - another all-in-one checker, this time from the Debian project.
* [HTML Dog](http://htmldog.com/) - Recommended HTML, CSS, and JavaScript tutorials.
* [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/) - Recommended reference and tutorials for web technologies.
* [List of tools for static code analysis](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) - on Wikipedia.

### Project Links

* [Canonical URL for the document](http://www.shlomifish.org/philosophy/computers/web/validate-your-html/) - on Shlomi Fish’s home site. That page should validate as XHTML 1.1.
* [GitHub repository](https://github.com/shlomif/validate-your-html) - contains the Markdown sources, an issue tracker and more resources. Contributions are welcome. Currently, that page does not validate, but it appears to be GitHub’s fault.

## Licence

This document is Copyright by Shlomi Fish, 2017, and is available
under the
terms of <a rel="license"
href="http://creativecommons.org/licenses/by/4.0/">the Creative Commons
Attribution License 4.0 Unported</a> (or at your option any
later version of that licence).

For securing additional rights, please contact
<a href="http://www.shlomifish.org/me/contact-me/">Shlomi Fish</a>
and see <a href="http://www.shlomifish.org/meta/copyrights/">the
explicit requirements</a> that are being spelt from abiding by
that licence.
