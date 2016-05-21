# enc2cmd
Interfacing encodings with rendering commands in LilyPond.

---

An important part of making LilyPond work in the domain of digital music edition is
the issue of visualizing editorial additions or special notation of any kind that
may be encoded in some way or the other, e.g. in [MEI](http://music-encoding.org).

This repository is currently a placeholder for a development that has to be conceived
and discussed from scratch.  Its aim is to create an infrastructure or API abstraction
so edition projects can create their custom packages of LilyPond commands and map
encoded “events” from the MEI to LilyPond commands.

From a bird view's perspective this means special encodings can be rendered by LilyPond.
And basically this also should create the path for supporting special notation (like
e.g. contemporary or mensural) in digital music editions.
