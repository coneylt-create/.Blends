# Blender Research Documentation

Research notes, practical explanations and supporting Blender materials by **Coneyl Taylor**.

This repository documents how Blender rigs and deformation systems work through inspection, controlled comparisons and illustrated walkthroughs. Materials are organised by study, with source credits, software versions and release information.

## Current study: Better Bends

**Better Bends: Corrective Bones in Blender** examines how an existing rig combines helper bones, stored vertex weights, constraints and pose-driven shape keys.

The study investigates the third-party **Royal Skies rig** and a localized hip-patch adapter fitted to Auto-Rig Pro. It documents and analyses an existing corrective system; it does not claim authorship of the original Royal Skies rig.

Supporting materials are being prepared for release, including:

- The research paper.
- The study’s `.blend` file.
- Annotated figures and pose comparisons.
- Instructions for inspecting the setup and repeating the comparisons by hand.

Files will be listed here as they are uploaded and approved for release.

## Recorded software environment

| Software | Version used |
|---|---|
| Blender | 5.2.0 LTS |
| Auto-Rig Pro | 3.79.20 |

These are the versions used for the documented study. Behaviour in other versions has not been established.

## Using the Blender study file

1. Download the file associated with the study’s specified release.
2. Open it in Blender and use **Save As** to create a working copy.
3. Follow **Appendix C** of the paper to identify the controls, establish a neutral pose and inspect the corrective responses.
4. Keep the pose, viewpoint, scale and configuration consistent when comparing results.

The supplied adapter contains a localized hip patch. The full-character comparisons in the paper come from the earlier source-character study.

Visual agreement alone does not reproduce every numerical result. The paper explains the measurements and the evidence needed to check them.

## Source asset and attribution

The Royal Skies rig is a third-party asset.

**Source listing:** [Royal Skies LLC – Royal Rig – Female2 9](https://sketchfab.com/3d-models/royal-skies-llc-royal-rig-female2-9-16be4b93768b4e419b2890f87a1f65bc), uploaded to Sketchfab by **donnaskuhn**.

The paper distinguishes the source rig from the study’s analysis, poses, visualisations and localized adapter. No endorsement by the original creator or uploader is implied.

## Licensing

Coneyl Taylor’s original text and analysis are licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).

Third-party models, rigs and other assets retain their own licences. The author’s licence does not relicense the Royal Skies asset or Auto-Rig Pro. Consult the source listing and any file-specific notices before redistributing third-party material.

## Releases, Zenodo and citation

Each published study release will identify:

- Its version and release date.
- The included files and changes.
- The software environment.
- The corresponding paper and supporting materials.
- Its Zenodo record and DOI, once published.

Use the specific release associated with the paper when checking or citing results. Citation details will be added when the publication record is available.
