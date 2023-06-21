<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Ashwani Rathee"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
prepath = "CompilerNotes.jl"
website_title = "Julia Compiler Notes"
website_descr = "Compiler Related Notes for Julia"
website_url   = "https://ashwani-rathee.github.io/CompilerNotes.jl/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
