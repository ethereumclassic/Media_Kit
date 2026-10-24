# SVG

The vector masters of the Ethereum Classic logo (rebuilt, not official files). Each file is one complete logo,
ready to place, with a transparent background: three groups, one per piece (`top`, `rhombus`, `chevron`). Each
group starts with a base shape (`top-base`, `rhombus-base`, `chevron-base`), exactly the piece's outline in one of
its facet colours, and on top of it holds the 8 facets as individual named shapes (`top-left`, `top-right`,
`rhombus-upper-right`, `rhombus-lower-left`, `rhombus-upper-left`, `rhombus-lower-right`, `chevron-left`,
`chevron-right`). Every facet is exactly its shape, edges are shared exactly: select a facet to recolour it, or a
group to move a piece. No masks, scripts, styles, transforms or text. The attribution is in a comment, the title
and description name the file as a rebuild.

| File | viewBox | Framing | Bytes |
|---|---|---|---|
| ethereum-classic-logo-full-colour-square.svg | `-746.2687 -246.2687 1492.5374 1492.5374` | square | 2163 |
| ethereum-classic-logo-full-colour.svg | `-309.6964 0 619.3928 1000` | tight | 2041 |
| ethereum-classic-logo-mono-square.svg | `-746.2687 -246.2687 1492.5374 1492.5374` | square | 2156 |
| ethereum-classic-logo-mono.svg | `-309.6964 0 619.3928 1000` | tight | 2034 |

Tight files: the viewBox is exactly the logo (width / height 0.6194). Square files: a
1492.5374 x 1492.5374 viewBox with the logo 67 % of the height and centred, as on the profile pictures; the
coordinates are the same as in the tight files. The root carries width and height equal to the viewBox size, so
tools that need an intrinsic size get the right aspect ratio. Scale to any size and keep the aspect ratio.

Why the bases: where two separate shapes share an edge, screen renderers let the background show through a little,
which shows as a thin grey line on a dark background. The base fills that edge from underneath. Base colour and
drawing order are chosen so each seam has one facet colour fully underneath and the other on top: the top piece
and the chevron have the left colour as base, then left and right; the rhombus has the upper-right colour as
base, then upper right, lower left, upper left, lower right. Delete the bases only for cutting or embroidery,
where every shape is cut or stitched on its own.

Colours (hex):

| Variant | Colours |
|---|---|
| Full colour | `#3cba3c`, `#0c8412`, `#166816`, `#034c03` |
| Mono | `#ffffff`, `#ececec`, `#e2e2e2`, `#d7d7d7` |

Facet colours in detail: [../README.md](../README.md#colours).

Works in every vector tool (Illustrator, Figma, Inkscape, Affinity, Canva, Office) and for production
(cutters, engraving, embroidery, print). For screens, web and social media the PNGs are still the best files:
they are rendered from a seamless model.
