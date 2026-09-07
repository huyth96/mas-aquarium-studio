# MAS Aquarium Studio

Public interactive prototype for Micro Aquatic Shop.

Open https://huyth96.github.io/mas-aquarium-studio/planner/

Arrange your aquarium in 2D, then choose **View my aquarium in 3D** to explore the same scene.

The standalone preview also opens at https://huyth96.github.io/mas-aquarium-studio/studio-3d/

## One aquarium, two views

- The 2D builder is the main editor. On a phone, select an object, choose **Move to a spot**, then tap its new position. Mouse dragging remains available.
- The fullscreen 3D preview reads the same complete scene: the tank footprint, individual objects, placement, scale and lighting. Its catalogue supports all 13 animal types, four plant types and four hardscape types.
- The arrangement is read-only in 3D. Orbit, zoom, switch camera angles or download an image; return to 2D to move, add or remove objects.
- Preview lighting and water controls can be applied back to the 2D scene as one undoable change. Opening and closing without changing these settings leaves the layout and history unchanged.
- Named projects and share links use the same complete aquarium data. There is no separate 3D project or save slot.
- A mobile Smooth rendering profile reduces resolution and rendering work. The 3D renderer loads on demand and is unmounted when the preview closes; the underlying 2D animation pauses while it is open.

This is a visual prototype with illustrative models, not a photorealistic simulator. Mobile settings are intended to reduce rendering work; performance has not been measured on a physical phone. It does not modify the Micro Aquatic Shop storefront.

## September 2026 update

- Emerald Passage opens at the default planner link: an open sand path, six plant groups, two distinct hardscape focal points and ten animals. Guppy, Harlequin rasbora and Ember tetra swim above the Neon tetras in clear upper and middle water.
- 13 animal types: 5 fish, 4 shrimp and 4 snails, placed individually.
- Four plant types: Anubias, Java fern, Crypt and Rotala.
- In 2D, fish cruise in full profile and turn only when completely beyond the glass edge; swimming pace, position and saved heading stay editable.
- Four stone and wood types with move, size, angle, mirror and lock controls in the 2D builder.
- Complete named aquarium projects saved locally on the device; editable scene sharing links.
- Lighting and water controls, zoom, focus view and image download.
- A grouped aquarium list links plants and animals to MAS product information. Actual hardscape is selected with the shop in store.

This repository contains the compiled public website. It is a layout illustration, not livestock compatibility or stocking advice. Most animal sprites are AI illustrations; the gold mystery snail is cut out from a MAS product photograph. Saved projects stay in the visitor's browser unless they choose to share a scene link.
