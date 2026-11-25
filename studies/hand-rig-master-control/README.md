# Hand Rig Study: Auto-Rig Pro and a Master Control

A bone-by-bone hand rig built in Blender 5.2, driven by Auto-Rig Pro and a one-control master.

## The question

Can a hand skeleton placed by eye, copying a video of a real hand, still produce a working rig in Auto-Rig Pro (ARP)? The short answer is yes, with a catch.

## What this file is

`Hand_ARP_master.blend` is the working build behind that test. Sixteen bones were placed into a hand mesh to match reference footage of a real hand opening, closing, spreading and curling. ARP could not edit that hand-built skeleton directly, but it used the joint positions as a map, built its own rig from them, added bones of its own (separate thumb and palm bones), and bound the mesh so it could move. A master control was then added so one slider poses several fingers together, the way the reference footage does.

## What worked and what did not

The finished rig matched the reference footage well on the key poses, including a four-finger curl. The thumb base was the weak point: the skin stretched unnaturally in some poses, which needs extra sculpting or weight painting to resolve. A hand-placed skeleton is a solid starting point for Auto-Rig Pro, provided you accept that ARP adds its own extra bones on top and budget extra time for the thumb.

## Software environment

| Software | Version used |
|---|---|
| Blender | 5.2.0 LTS |
| Auto-Rig Pro | 3.79.20 |

Same environment as the Better Bends study. Behaviour in other versions has not been established.

## Using the file

1. Download the file for the release tied to this study.
2. Open it in Blender and use Save As to work on a copy.
3. The full method, measurements and pose comparisons are documented in the accompanying paper, *Hand Rig Study: Auto-Rig Pro and a Master Control*.
4. Keep pose, viewpoint and scale consistent when comparing results against the paper.

## Source material

Reference footage: *Smart Hand System* by Hernan Ares, and a layout reference still by Trystan Bleuven. Neither source demonstrates an ARP build; both were used for pose targets and bone layout only.

## Licensing

Coneyl Taylor's original analysis and rig work are licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Reference footage credited above retains its own rights; this licence does not extend to it.

## Releases, Zenodo and citation

This study is paired with a paper being prepared for Zenodo publication. Its release details, DOI and citation format will be added here once the record is live.
