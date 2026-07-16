# nelepope-redirect

Redirects the old domain (nelepope.com) to penelopesaintgeorge.com.

- `index.html` redirects the root.
- `404.html` catches every other path and forwards it, preserving the path
  (e.g. nelepope.com/retinoids.html -> penelopesaintgeorge.com/retinoids.html).
- `CNAME` claims nelepope.com for this repo.

The live site itself lives in the nelepope.github.io repo.
