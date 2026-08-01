just a linktree kinda website i have full control over as i didnt like the restrictions linktree gave me when using it

live at https://bewfordq.github.io/LnkTree/

## structure

the site is published from `docs/` (github pages), so anything the page uses has to live in there.

```
docs/
  index.html              the whole site, styles and scripts included
  assets/
    bugcat/               bugcat sticker gifs (cat zone)
    rainbow-dash/         rainbow dash gifs (dash zone)
    img/                  profile picture and the bottom image
archive/                  images not used by the site, kept just in case
```

to add a gif to a zone: drop the file in the matching `assets/` folder, add an
`<img class="throwable">` cell to that zone's grid in `index.html`, then add the
filename to that zone's list in `RAIN_SETS` so it also shows up in the rain easter egg.
