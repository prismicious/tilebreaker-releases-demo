# Tilebreaker demo

**[Play the demo here](https://prismicious.github.io/tilebreaker-releases-demo/)**

A blockbreaker with no paddle. The field starts as one solid pastel slab with a
2x2 pocket carved in the middle of it, and nothing in the pocket: a run opens on
the skill tree, and the first thing in the tree is the first ball. Every tile a
ball hits is gone for good, so the room you are trapped in becomes the room you
play in.

The demo is the first board: the run, its first fractalization, and the end
card. The whole game is at
**[prismicious.github.io/tilebreaker-releases](https://prismicious.github.io/tilebreaker-releases/)**.

## About this repository

It exists to serve that one link. The `gh-pages` branch holds the demo's web
build, pushed here by the game's own repository when a version is released, so
the link is always the newest released demo. There is no source code here and
nothing to download.

The demo is not a separate game. Each release builds it from the same commit as
the full game, with the full game's own content left out, and checks before
publishing that every script in it is the full game's script.
