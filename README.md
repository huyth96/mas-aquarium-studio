# MAS Aquarium Studio

Public interactive prototype for Micro Aquatic Shop.

Open https://huyth96.github.io/mas-aquarium-studio/planner/

## Arrange, explore, review

- Build directly inside a fixed-angle orthographic aquarium. Select and drag objects in space, rotate plants and hardscape, and switch between right, left and overhead views. Photo layout and Measured map remain available; View in 3D opens the same layout as an animated scene.
- Search and filter a 21-item catalogue: four plants, thirteen animals and four hardscape illustrations. Product cards use shop photographs where available; aquarium objects remain illustrations.
- The product panel sits beside the aquarium on desktop and opens from the bottom on mobile. Desktop users can drag a catalogue item into the tank. On mobile, Add places one object immediately and opens its touch controls. Use large Move arrows, Size and Rotate tabs, or drag directly. Objects opens a dedicated list for selecting hidden items. The mobile workspace fits the viewport and its compact catalogue keeps Add buttons visible. Size, rotation, undo, named projects and scene sharing are preserved.
- Your selection groups placed objects and keeps purchase quantities separate from layout counts. Actual sale options include individual animals, packs, pots and plant bundles.
- Seventeen linked shop products have dated AUD guide prices and verified variant mappings. Availability checks only accept known product and variant IDs with unchanged option titles. Current prices, stock, shipping and checkout are reviewed at MAS via a Shopify cart permalink.
- Stone and wood remain in-store consultation items and are excluded from the online cart.
- The builder renders only when the scene or controls change; it does not animate animals while arranging. The animated 3D preview loads on demand, replaces the builder renderer while open, and closes back to the same editable aquarium. Mobile uses reduced rendering detail.

## Prototype limits

This is a visual planning prototype, not a physical simulator or stocking/compatibility adviser. Product sale-size notes are shown separately from illustration scale; images and mature plant groups do not claim exact delivered dimensions. Accurate product calibration needs consistent measured assets from the shop.

Guide prices were checked on 8 September 2026. Final prices and stock are confirmed at MAS. Purchase choices are session-only; named aquarium layouts are stored in the visitor's browser and can be shared by scene link. This repository contains the compiled prototype and does not alter the MAS Shopify theme. Physical-phone performance has not been measured.

Spatial objects are simplified procedural 3D models. In the optional Photo layout, most aquarium sprites are AI illustrations; the gold mystery snail uses a cutout from a MAS product photograph. The optional standalone 3D preview is at https://huyth96.github.io/mas-aquarium-studio/studio-3d/.
