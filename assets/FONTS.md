# The faces in this folder

Extracted from the page's base64 on 27 August 2026 and named by the first
twelve hex of their sha256. Both copyright lines were read out of the binaries'
own `name` tables.

Both families are under the SIL Open Font License, Version 1.1 — see `OFL.txt`
beside this note. The license's second condition asks that redistributed copies
carry the notice and the license; that is what these two files are.

| File | Family | Copyright |
| --- | --- | --- |
| `99d6c78e0437.woff2` | Fredoka Light | Copyright 2016 The Fredoka Project Authors (https://github.com/hafontia/Fredoka-One) |
| `b7753f30f8bd.woff2` | Comic Neue Regular | Copyright 2014 The Comic Neue Project Authors (https://github.com/crozynski/comicneue) |
| `13e9f12e3a02.woff2` | Comic Neue Bold | Copyright 2014 The Comic Neue Project Authors (https://github.com/crozynski/comicneue) |

The other two files here are not fonts: `d172d13f3f2c.jpg` is the banner
illustration and `d21be918b5fd.pdf` is the blank intake form, both of them
yours.

One mismatch, pre-existing and harmless: the `@font-face` rule in `index.html`
declares `font-family: 'Fredoka'` with a variable weight range of `300 700`,
but the file is a static Fredoka **Light**. The browser synthesises the rest.
Worth fixing whenever that page is next touched.
