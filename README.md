**WARNING!!** This file is now generated by gmake . DO NOT MODIFY directly!

# Motivation

To educate the world about the benefits of making sure their markup of [HTML](http://en.wikipedia.org/wiki/HTML) and other Web and non-Web languages is valid according to the web standards.

# What is valid HTML markup?

Most web browsers will accept various variations in the HTML markup language, but often will not know exactly what to do, unless the markup is well-formed and strictly abides by the WWW standards. To make it easier for browsers, for other HTML consumers and processors, and for general good measure, one should make sure the HTML **validates** and thus is **valid**.

# Why validate?

- By validating your pages, you make sure the structure of the document is acceptable to standards-compliant browsers.
- When you deviate from the standard, you don't know how the browser is going to react.
- Saying that “I don’t know if my site is standards compliant or not, but it looks good in all browsers.” (or just in one browser and one platform on which it was tested) is not a good idea.
- The browsers may not display this page correctly in future versions, or a new browser may do things differently.
- (For instance, when [Microsoft Internet Explorer (MSIE)](https://en.wikipedia.org/wiki/Internet_Explorer) version 5.0 came, it was more standards-compliant than MSIE 4.x and as a result many sites that worked with IE before became broken. This happened in the release of MSIE 6.0, and in Windows XP Service Pack 2, as well.)
- The browser has a tough job as it is, so you shouldn't make it tougher by sending it mal-formed input.

## Caveats

- Standards-compliance is not a panacea.
- Even if all the output from the site is standards-compliant. it doesn't mean it will display correctly.
- This is either because of bugs in the browsers, or because you have not done the right thing.
- So, it is important to test the pages in as many browsers as possible, in addition to validating them.

# How to validate?

A [DuckDuckGo search](https://duckduckgo.com/?q=html+validator&ia=web) for “html validator” as well as a [Google search](https://encrypted.google.com/search?hl=en&q=html%20validator) will yield many results. Note that you should first choose a version of the HTML or XHTML standards (such as [HTML5](https://en.wikipedia.org/wiki/HTML5) or [XHTML5](https://en.wikipedia.org/wiki/HTML5#XHTML_5_(XML-serialized_HTML_5))) and use their correct [Doctype](https://en.wikipedia.org/wiki/Document_type_declaration) to indicate that you are using them. Different HTML pages (even ones on the same site) may adhere to different versions of the standards, and validate accordingly, as long as they specify the appropriate doctypes.

## Some prominent validators

- [The W3C validator](https://validator.w3.org/)
- [HTML Tidy](http://www.html-tidy.org/) - a library and a command-line program for validating and fixing HTML. It is recommended to run it with all warnings displayed.

# The more general case: linting and validating

WWW Markup Validation is a specific case of [“linting”](http://stackoverflow.com/questions/8503559/what-is-linting) where one runs a program to make sure bad idioms are not present in one’s code or markup. There are links to more linters and checkers below.

Also see ["awesome linters" on GitHub](https://github.com/caramelomartins/awesome-linters) which lists many good linters.

# Links

- [Coding Horror: “HTML Validation: Does It Matter?”](https://blog.codinghorror.com/html-validation-does-it-matter/)
- [Perl Elements to Avoid](http://perl-begin.org/tutorials/bad-elements/) and [“What are some best practices in programming that I should adopt?”](https://github.com/shlomif/Freenode-programming-channel-FAQ/blob/master/FAQ_with_ToC__generated.md#what-are-some-best-practices-in-programming-that-i-should-adopt) - mention other good practices.
- [tidyall](https://metacpan.org/pod/distribution/Code-TidyAll/bin/tidyall) - an all-in-one linter, validator and tidier.
- [check-all-the-things](http://bonedaddy.net/pabs3/log/2016/07/04/check-all-the-things/) - another all-in-one checker, this time from the Debian project.
- [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/) - Recommended reference and tutorials for Web technologies.
- [HTML Dog](http://htmldog.com/) - Recommended HTML, CSS, and JavaScript tutorials.
- [List of tools for static code analysis](http://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis) - on Wikipedia.

## Project Links

- [Canonical URL for the document](http://www.shlomifish.org/philosophy/computers/web/validate-your-html/) - on Shlomi Fish’s home site. That page should validate as XHTML5.
- [GitHub repository](https://github.com/shlomif/validate-your-html) - contains the DocBook sources, an issue tracker and more resources. Contributions are welcome. Currently, that page does not validate, but it appears to be GitHub’s fault.
