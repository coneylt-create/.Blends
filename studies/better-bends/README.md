# Better Bends: Corrective Bones in Blender

An exploratory case study of helper bones and corrective shape keys in an existing character rig, with a localized transfer to Auto-Rig Pro.

## The question

Does adding helper bones and corrective shape keys to an existing rig actually improve a hip crease during deformation, and can that local fix be transferred onto a different rig setup without rebuilding the whole character?

## What this file is

`royalrig-arp-full-thigh-adapter.blend` is the working file behind that test. It documents the hip region of the third-party **Royal Skies** character rig (191 vertices, 342 triangles in the measured patch), comparing how the surface changes under passive deformation, helper bones alone, shape keys alone, and the two combined. A custom axis conversion and full-thigh reader/deformer then reproduces that hip patch on a localized Auto-Rig Pro adapter, checked against 11 static poses.

## What worked and what did not

At 90° of left forward flexion, mean absolute local triangle-area change came out at 21.23% passive, 33.91% with bones only, 22.36% with shape keys only, and 33.75% combined. The helper-bone response gave a visibly softer front hip crease, but with more local area change than the shape-key version, so "looks better" and "distorts less" pulled in different directions. The ARP transfer held up well: the localized adapter matched the source hip patch across all 11 poses to within 6.54 × 10⁻⁷ Blender units.

This study documents an existing corrective mechanism and its localized integration. It does not establish volume preservation, anatomical accuracy, or freedom from self-intersection, and it does not propose a new skinning algorithm or a validated whole-character pipeline.

## Software environment

| Software | Version used |
|---|---|
| Blender | 5.2.0 LTS |
| Auto-Rig Pro | 3.79.20 |

Same environment as the Hand Rig Master Control study.

## Using the file

1. Download the file for the release tied to this study.
2. Open it in Blender and use Save As to work on a copy.
3. The full method, pose inputs and measurements are documented in the paper, *Better Bends: Corrective Bones in Blender*, published on Zenodo (DOI [10.5281/zenodo.24426948](https://doi.org/10.5281/zenodo.24426948)).
4. Keep pose, viewpoint, scale and configuration consistent when comparing results against the paper.

## Source asset and attribution

The Royal Skies rig is a third-party asset: [Royal Skies LLC – Royal Rig – Female2 9](https://sketchfab.com/3d-models/royal-skies-llc-royal-rig-female2-9-16be4b93768b4e419b2890f87a1f65bc), uploaded to Sketchfab by **donnaskuhn**. The paper distinguishes the source rig from the study's own analysis, poses, visualisations and localized adapter. No endorsement by the original creator or uploader is implied.

## Licensing

Coneyl Taylor's original text and analysis are licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Third-party models, rigs and other assets retain their own licences. This licence does not relicense the Royal Skies asset or Auto-Rig Pro.

## Releases, Zenodo and citation

Published as *Better Bends: Corrective Bones in Blender*, Zenodo, DOI [10.5281/zenodo.24426948](https://doi.org/10.5281/zenodo.24426948). Use the specific release associated with the paper when checking or citing results.
