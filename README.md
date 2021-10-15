# IBF Working paper template

A simple working paper template based on the research papers at the Institute of Banking and Finance, Leibniz University Hannover.


# Installaton

The template is maintained as a package. To install, please use

```
devtools::install_github("SebSchroen/wp_template")
```

# Usage

To start a working paper from the template, either use:

```
rmarkdown::draft("new_paper.rmd", "ibf-working-paper", package = "wptemplate", create_dir = "default")
```

Or go to File -> New File -> RMarkdown -> From Template in RStudio.

## License

This template is based on the [pandoc default template](https://github.com/jgm/pandoc-templates) by John MacFarlane. The template is licensed as follows:

All of the templates in this repository are dual licensed, under both the GPL (v2 or higher, same as pandoc) and the BSD 3-clause license (included below).

Copyright (c) 2014--2019, John MacFarlane

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

  + Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

  + Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

  + Neither the name of John MacFarlane nor the names of other contributors may be used to endorse or promote products derived from this software without specific prior written permission.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
