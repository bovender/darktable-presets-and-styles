# Darktable presets and styles

Presets and styles for [Darktable][] from an amateur photographer and photo editor.

These are my own few presets and styles and they will grow over time.

This is heavily inspired by the work of [Boris Hajdukovic][] and his tutorials
on Youtube, but I would like to stress that **these are neither officially Boris'
presets** (as far as I know, he does not publish his presets), nor is this in any
way endorsed by Boris. In fact, while I follow him and admire his work, he does
not know me at all.

I put these presets and styles into the public domain (CC0 license) for others
to use and build upon.

## A big 'thank you'

I would like to express my deepest gratitude to Boris for taking the time and
putting all the effort into making his tutorial videos. I have learned a lot
from him, and I keep on learning.

## Important disclaimer

Please note that I am really only an amateur and I am still learning to edit
photos with Darktable. If you are interested in these files, be aware that
these files may very well not meet your needs, lead to funny results, or just
simply be "wrong". So use at your own risk, but I hope this is helpful.

The main purpose of this repository is to keep track of my own editing skills,
and as an additional backup.

## Branches in this repository

I will keep branches named after the Darktable release versions that I had in
use when I created or updated the presets and styles. I will merge the current
versioned branch into `main` so that `main` always reflects the latest versions
of my presets.

## Hints for reading the tables

| module  | Name of the Darktable module that this preset refers to |
|---------|---------------------------------------------------------|
| file    | name of the file in this repository                     |
| episode | episode of Boris' "Editing with Darktable" series       |  
| remarks | comments on the intended usage                          |

## Presets

| module  | sigmoid                                                 |
|---------|---------------------------------------------------------|
| file    |  `neutral gray sRGB Boris.dtpreset`                     |
| episode | [Darktable Episode 88: sigmoid and contrasts][88]       |
| remarks | This is based on the built-in preset `neutral gray` with `preserve hue` set to `0.00%` and `base primaries` set to `sRGB`. Must also apply some contrast-enhancing method, e.g. with the `tone equalizer` module. |

| module  | tone equalizer                                          |
|---------|---------------------------------------------------------|
| file    |  `inverted linear Boris.dtpreset`                       |
| episode | [Darktable Episode 88: sigmoid and contrasts][88]       |
| remarks | Use in conjunction with `neutral gray sRGB Boris` in `sigmoid`. Intermediate edit; results in very low-contrast image. Must apply contrast-enhancing preset in second instance of `tone equalizer`. |

## Examples of my photography

If you are interested in what kind of photos a take and make, head
over to my personal homepage:
[bovender.de/tags/photos](https://www.bovender.de/tags/photos).
This is currently only a negligible collection, but it will grow.
(I do have thousands of photos on my disk ;-) .)

[Boris Hajdukovic]: https://www.youtube.com/@s7habo
[Darktable]: https://darktable.org
[88]: https://youtu.be/KnLtGS_mRi8?si=nxN_UJefCRhB4oXo