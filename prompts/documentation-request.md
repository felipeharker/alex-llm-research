# README FOR ALEX-DESIGN-DOCS

## OBJECTIVES

I want to create some simple, effective documentation for this repository.

My understanding of application/system and/or process documentation is limited. Agile Documentation Practices seems to be a solid system to work with. I am open to other approaches, and the format, contents, writing style, etc. are variable.

## ABOUT THE REPOSITORY

Alex Design Docs serves as the home and primary location for documents related to standards created and distributed by Alexandria- the standards documents include the following:

### CONTENTS

#### working-template_v1.2.1.3dm

this is a document containing the accepted practices for digital drafting and modeling in Rhinoceros 8. 

The document includes layers and sublayers, saved views, materials, lights, pre-made text formatting/styles for callouts, dimensioning, etc., standardized naming and labels.

most importantly, the model file contains living examples of how to draft (2D), annotate, dimension, and organize 2-dimensional drawings as well as multiple examples of 3D modeled signage, located at saved positions for rendering and visualizing. this is functionally the hub for all design practice standards.

this document works in conjunction with render-settings to serve as a master document for designing and visualizing with v-ray.

this document works in conjunction with working-template_v1.2.1.gh. the .gh file is the standard for creating Grasshopper definitions which are paired with Rhino models.

// model note: both render settings and grasshopper definitions will be explained further later

#### working-template_v1.2.1.gh

Grasshopper is the native parametric/computational design plugin for Rhino.

this document serves as a baseline standard for grasshopper definition files. the standards include (but are not limited to) grouping, color coding, labeling; data type best practices, data tree workflows, and user input standards (for numbers, data trees, geometries, etc.)

// model note: this is still under development, but ideally it will be as fully built as the rhino standards counterpart

#### ./configs/render-settings

this sub-directory contains the default day and night render settings files (v-ray object filetype). users will now "swap" render settings within v-ray and in the same rhino model file to create renders at different times of day.

#### resource-lib_v1.0.0.3dm

this is a living graphic resource and reference library which is in early development.