# ppgen README

This VScode extension provides support for [ppgen][].

[ppgen][] ([Github][ppgen_git]) is a post-processing generator for [Distributed
Proofreaders][dp]. It parses a source file and outputs in a number of formats,
including Latin-1 text, UTF-8 text, and HTML.

[ppgen]: https://www.pgdp.net/wiki/PPTools/Ppgen
[ppgen_git]: https://github.com/wf49670/ppgen
[dp]: https://www.pgdp.net/

What is [Distributed Proofreaders][dp]? Here's the site concept in their own
words:

> Distributed Proofreaders provides a web-based method to ease the conversion of
> Public Domain books into e-books. By dividing the workload into individual
> pages, many volunteers can work on a book at the same time, which significantly
> speeds up the creation process.
>
> During proofreading, volunteers are presented with a scanned page image and
> the corresponding OCR text on a single web page. This allows the text to be
> easily compared to the image, proofread, and sent back to the site. A second
> volunteer is then presented with the first volunteer's work and the same page
> image, verifies and corrects the work as necessary, and submits it back to the
> site. The book then similarly progresses through a third proofreading round and
> two formatting rounds using the same web interface.
>
> Once all the pages have completed these steps, a post-processor carefully
> assembles them into an e-book, optionally makes it available to interested
> parties for 'smooth reading', and submits it to the Project Gutenberg archive.

Please [visit the site][dp] and consider volunteering if this sounds interesting
to you! While some roles at DP can be time-consuming, even proofreading a single
page per day is helping. Every volunteer counts!

## Features

So far, this extension offers syntax highlighting for the ppgen source file.

Future plans include:
- auto-completion for dot commands
- a command to build the document and display the output in VScode as a preview

## Release Notes

### 0.0.1

Initial release. Supports syntax highlight for `*-src.txt` files.
