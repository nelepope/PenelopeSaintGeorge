# PenelopeSaintGeorge

Redirects the **old** domain (nelepope.com) to penelopesaintgeorge.com.

Despite the name, this repo is not the website — it is a redirect stub.
The live site lives in the `nelepope.github.io` repo.

- `index.html` redirects the root.
- `404.html` catches every other path and forwards it, preserving the path
  (e.g. nelepope.com/retinoids.html -> penelopesaintgeorge.com/retinoids.html).
- `CNAME` claims nelepope.com for this repo.
