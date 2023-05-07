Daz Scripts
===

Collection of Daz3D scripts that I've written or use.

Each of *my* scripts are MIT licensed. Third party scripts come with their own or none if the original
author wasn't reachable.


## Usage

[Download](https://github.com/chrsm/dazzed/archive/refs/heads/master.zip) this
as a zip, extract the contents to `YOUR_DAZ_LIB\Scripts`. Inside Daz3D, use
the content library and look at `Scripts > chrsm`.


## Scripts


### [SwapNode.dsa](chrsm/SwapNode.dsa)

Swaps the position of two nodes. Does not modify anything else.


### [Look At Null.dsa](chrsm/Look At Null.dsa)

Creates a new null/empty node and makes the selected nodes point at it with their left & right eyes.
The new node has the same wspos as the current view.

If selected nodes do not have 'Left Eye' and 'Right Eye', they are skipped!


## Third-party Scripts


### [Recenter.dsa](chrsm/Recenter.dsa)

**DISCLAIMER: I DID NOT WRITE THIS. I simply formatted it.**
**COPYRIGHT LICENSE DOES NOT APPLY TO THIS FILE!**
**See header in file for full credits and a link to the forum thread.**

[recenter.dsa](recenter.dsa) recenters the world around the selected object.

This is useful for many scenarios, but the reason I have needed it is due to
Daz bugs when objects are too far from the world origin (black eyes, haircap
poke-through, etc).


### [FixPointAt.dsa](chrsm/FixPointAt.dsa)

**DISCLAIMER: I DID NOT WRITE THIS. I simply refactored it.**
**COPYRIGHT LICENSE DOES NOT APPLY TO THIS FILE!**
**See header in file for full credits and a link to the forum thread.**

Ever had eyes perfectly lined up with the PointAt constraint? Then re-opened
the same scene later to see that they're not pointed correctly?

FixPointAt fixes point-ats within your scene so that transforms are saved.
Simply run this before saving your scene.


