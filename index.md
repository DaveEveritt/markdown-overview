# Markdown

![](images/mmd-plain-text.jpg "The case for plain text, image of a typewriter (from somewhere MultiMarkdown-related I can't recall)")

<small>NOTE: use the arrow/cursor keys or icons (bottom right) to navigate</small>


# Teaching Innovation Project

**Aim:** "A standard template and guide for a system to generate module handbooks in .epub and .mobi formats (iPhone/iPad, Android, Kindle), and PDF, from a single plain-text document using free services and software, including [LeanPub](https://leanpub.com/)."  
contact: [deveritt@dmu.ac.uk](mailto:deveritt@dmu.ac.uk)


# Learning materials

From Markdown, you can generate…

1. HTML
1. Word
1. PDF
1. e-books
1. web-based presentations (Powerpoint not accessible/web-friendly)

…from single or few text-based source document(s), then you can fiddle with the formatting.


# Fighting lock-in

(suitable clickbait graphic here)

**Office suite developers hate this Melton Mowbray lecturer!**  

**One secret trick Microsoft and Apple don't want you to know!**


# QUERTY

- The **QUERTY** keyboard prevented typists locking up from going too fast, but has itself become *locked-in*
- The most **popular isn't always the best**. Office suites are from the 80s. The web and semantically-structured text is the ideal delivery platform.


# No lock-in!

- Free yourself from applications and their compatibilities!
- Your text doesn't depend on **any** proprietary software!
- Generate proprietary formats if you need/must!


# Plain text formats

- Lightweight, small file sizes e.g. `.md` or `.txt` vs `.ppt`
- No software version incompatibility (e.g. old Word can't open new Word)
- Future-proof
- Machine-readable, therefore more accessible
- Portable and platform/device independent


# What is Markdown

- Developed in 2004 by [John Gruber](https://daringfireball.net/projects/markdown/)
- there is an emerging standard: [CommonMark](http://commonmark.org/)

-------------

## easy to read/write/edit

> The aim is to make it easy to read, write, and edit prose. HTML is a publishing format; Markdown is a writing format…

## easy to sharing between devices/people

> Unlike cumbersome word processing applications, text written in Markdown can be easily shared between computers, mobile phones, and people. It’s quickly becoming the writing standard for academics, scientists, writers…

–[Daring Fireball (John Gruber)](https://daringfireball.net/projects/markdown/syntax)

## gentle learning curve

> Formatting text in Markdown has a very gentle learning curve. It doesn’t do anything fancy like change the font size, color, or type. All you have control over is the display of the text… making things bold, creating headers, and organizing lists."

–[MarkDown tutorial](http://www.markdowntutorial.com/)


# Extended Markdown

MultiMarkdown is maintained by [Fletcher Penney](http://fletcherpenney.net/) and [extends the original Markdown syntax](https://daringfireball.net/projects/markdown/syntax) with [extra features](https://rawgit.com/fletcher/human-markdown-reference/master/), including [epub generation](http://fletcherpenney.net/multimarkdown/) (although this can also be done with other conversion tools).

<small>[markdownguide.org - Extended Syntax](https://www.markdownguide.org/extended-syntax) gives a brief summary of some now-common extended Markdown, including tables.</small>

# Markdown flavours

There are a few [Markdown flavours](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors) although many are similar and some are trivial. There are also attempts to [standardise Markdown variations](https://github.com/jgm/CommonMark/wiki/Deployed-Extensions).

However, most **Markdown** parsers and/or **Multimarkdown** are likely to have everything most people commonly need.


# Other lightweight markup languages

- [Textile](https://github.com/textile)
- [reStructuredText](http://docutils.sourceforge.net/rst.html)
- And more…

<small>…although **Markdown** has become the most widely-supported and well-documented with converters in every widely-used programming language.</small>


# The web and Markdown

- with static site generators, you can use Markdown to build an entire wesite or maintain a blog
- there are static site generators in almost every programming language e.g. (hover for language) [Nanoc](https://nanoc.ws/about/ "Ruby") and [Jekyll](https://jekyllrb.com/ "Ruby"), [Hakyll](https://jaspervdj.be/hakyll/ "Haskell"), [Sculpin](https://sculpin.io/ "PHP"), [Hugo](http://gohugo.io/ "GoLang")…

See [staticSiteGenerators.net](https://staticsitegenerators.net/)


# Two tiers of use:

Use Markdown quickly without a little learning, or deeply by learning more

- **essential:**  
  prepare handbooks and documents, learning materials, HTML, quickly structure content
- **advanced:**  
  version control with GIT, continuous deployment with a permanent URL on GitHub pages, CSS styling for HTML output, e-books…


# Why bother?

Why use Markdown?

[How to Write Faster, Better & Longer: The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/) —John O'Nolan


# Hardcore questions:

**Q. Why not just use LaTeX?**

- A. Markdown can be a quick start for generating a LaTeX document to expand later
- A. Markdown is sufficient for many general documents
- A. Markdown has minimal setup overheads
- A. simpler markup is more future-proof


# Softcore question:

**Q. Why not stick to Office suites?**

- A. They're not naturally web-friendly
- A. They don't encourage semantically-structured content
- A. Office suites don't easily transport between formats
- A. WYSIWYG formatting can be lost (e.g. fonts)


# Advantages

- Highly portable
- Future-proof
- Semantic structure is accessible and machine-readable (screen readers)
- creates semantic and accessible outputs
- Multiple Markdown editing options: from plain text to dedicated visual editors
- Editable on any device and platform
- minimal and writing-focussed


# Disadvantages

- Not an immediately visual environment
- Resistance to change from familiar software
- prior investment in existing skills
- The ubiquitous dominance of Microsoft as a *primary* source
- Attachment to personal formatting (colours, fonts...)
- some conversions and advanced features require installs


# Markdown issues

- limited set of tags with no HTML5 semantic tags
- some parsers do/don't allow inline HTML/attributes
- no *direct* way of adding maths

but:

- MultiMarkdown supports LaTeX/MathJax syntax `$10^2$`
- You can use [MathJAX](https://www.mathjax.org/) in your HTML
- Some converters support [Math markup in Markdown](https://github.com/cben/mathdown/wiki/math-in-markdown)

<small>
e.g. $ delimiters with Pandoc: `${e}^{i\pi }+1=0$`  
gives: ${e}^{i\pi }+1=0$
</small>


# Writing Markdown

## most programming text editors

- [Atom (free)](https://atom.io/)
- [VSCode (free)](https://code.visualstudio.com/)

## dedicated Markdown editors…

- [iA Writer (paid)](https://ia.net/writer/)
- [Write! App (paid)](https://writeapp.co/)

## Many more free or inexpensive:

- [free/paid Markdown editors](http://alternativeto.net/software/ia-writer/)
- [free/paid Windows Markdown editors](http://alternativeto.net/software/ia-writer/?platform=windows)


# Markdown resources

Selection in progress, but for now:

- [GitHub marked](https://github.com/chjj/marked/blob/master/README.md) - parse and compile Markdown in HTML with JavaScript.
- [GitHub-Flavoured Markdown (GFM): Markdown table syntax](https://help.github.com/articles/organizing-information-with-tables/)
- [Dillinger: convert Markdown to styled HTML](http://dillinger.io)
- [RMarkdown and Reveal for data presentations](http://rmarkdown.rstudio.com/revealjs_presentation_format.html)
- Brett Terpsta's [Markdown Service Tools](http://brettterpstra.com/2013/03/08/new-in-the-markdown-service-tools-in-place-markdown-to-rtf/) - OS X MultiMarkdown install
- [Pandoc: universal document converter](http://www.pandoc.org/installing.html)


# Acknowledgements

Presentation made with [Reveal.js](http://lab.hakim.se/reveal-js/#/), using [RJSMake](https://github.com/eosrei/rjsmake) to generate the presentation directly from a single Markdown file.

See the [raw Markdown](https://raw.githubusercontent.com/DaveEveritt/markdown-overview/master/index.md) or [the HTML generated from this Markdown](https://github.com/DaveEveritt/markdown-overview/blob/master/index.md). The [source code](https://github.com/DaveEveritt/markdown-overview/) is available for download/cloning, and you can [report any issues](https://github.com/DaveEveritt/markdown-overview/issues).
