# Frontend Mentor - 3-column preview card component

## What I learnt

CSS Grid: two-dimensional grid-based layout

Terminology:
- grid container: the parent of all grid items
- grid item: children of grid container
- grid line: dividing lines - horizontal and vertical
- grid cell: a single cell within the grid
- grid track: columns or rows
- grid area: any number of grid cells

Properties of parent:

display: grid

grid-template-columns
grid-template-rows
- can name them
- number of rows/columns and length
- 1fr - a fraction of available space (e.g. 1fr 1fr 1fr - 3 columns/rows each a third of available space)

grid-template-areas - referencing names of the grid using grid-area property
- grid-area - children property, used to name the grid cell/area

justify-items & align-items: aligns grid items
- can also be achieved using justify-self property on individual grid items.

justify-content & align-content: aligning the grid within grid container (when total grid size is smaller than grid container)


## Useful resources:
https://css-tricks.com/snippets/css/complete-guide-grid/
