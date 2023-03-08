# Composible Stencils for Electronic Schematic Diagrams




## Line Weight

The stencil set uses two line weights: 2pt for primary lines, 1pt for secondaries. I think the proportion scales fairly well.

## Color/Tone

The stencil set uses this palette:

Color    | Hex Code | Notes                          |
-------- | -------- | ------------------------------ |
Black    | #000000  | Base color for stencils        |
Shale    | #656565  | Variable arrows                |
Graphite | #999999  | Electrolytic Capacitor cores   |
Aluminum | #A5A5A5  | Notation arrows, legend border |

If a two-tone representation is needed, a possible solution may be:

* Make the variable arrows back with a think white border
* Use hatching for the capacitor cores
* Use a dashed line for notation arros and legend border

## Fonts

Part labels are set in Anonymous Pro with extra kerning.

Information labels and the legend are set in Fira Mono.

The stencil set uses a 10pt font except for pin identifiers, which are set at 8pt.

Justification is set to allow labels to grow away from the component; if a layout problem requires moving the label around, changing the justification may be needed.

## Magnets

If you are using OmniGraffle, magnets are available.

Traces are intended to be drawn with the Orthogonal Line style, except as needed (rectifier networks, etc.).

