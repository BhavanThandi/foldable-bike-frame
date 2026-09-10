# Foldable Bike Frame for Urban Commuters

**ENSC 204 – Group 15 (UrbanGear Innovations)**
Simon Fraser University, Fall 2025

A compact, durable folding bicycle frame designed for people who commute in the city and need a bike that can be carried onto transit, stored in a small apartment, or tucked into a car trunk. The frame folds in half around a single structural rod along the bottom of the frame, and the handlebars self-align during the fold so nothing collides.

This repository holds the SolidWorks models, engineering drawings, the original concept sketch, and prototype demo videos.

## Team

| Member | Role |
| --- | --- |
| Bhavan Thandi | Design lead – set the project direction, ran concept selection, and delegated modelling, drawing, and testing tasks according to each member's strengths |
| Vardeep Grewal | Team member |
| Surjit Taneja | Team member |
| Joban Gill | Team member |
| Harsevak Yadav | Team member |
| Arnav Ramkar | Team member |
| Ishaan Hothi | Team member |

## The problem

Full-size bikes are awkward to bring on buses and trains, take up a lot of space at home, and are easy targets for theft when locked outside. Existing folding bikes tend to be either heavy, fiddly to fold, or expensive. The goal was a frame that:

- folds into a sleek, compact shape that is easy to carry
- stays light and structurally sound when unfolded
- can be manufactured with straightforward processes and minimal hardware
- keeps the rider stable and keeps folding parts clear of each other

## Design process

The project went through several iterations before settling on the final frame.

1. **Initial sketching.** The first ideas are in `Initial Sketch.pdf`. Early concepts included a frame that folds handlebars and tubes into a single compact "tube" shape, a lock-and-clip seat tube, an adjustable frame whose size could change with the rider, and a fold that lets the bike stand on its own. Several of these were marked "too simple" or crossed out and fed into the next round.
2. **Three folding concepts.** The team developed and compared three distinct mechanisms:
   - a mid-frame rotation, where the frame pivots at its centre
   - a wheel-pivot mechanism, where the front wheel assembly swings to the side
   - a rod-hinge system, where a lower rod acts as the folding axis
3. **Concept selection.** Each concept was evaluated on structural strength, folding efficiency, and how realistic it was to build within the project scope. The design with the most reliable and dependable folding motion was carried forward.
4. **Detailed design and modelling.** Every part was modelled in SolidWorks, assembled, and documented with dimensioned drawings. Parts were revised more than once; the "(SECOND ONE)" files are the later revisions of the hardware.
5. **Prototype and testing.** A physical prototype was built and the folding and rotating mechanism was tested. Recordings are in `Videos/`.

## Final design

- **Single lower rod as the folding axis.** One structural rod runs along the bottom of the frame and connects the front and rear sections. It is the main axis and the anchor point for the folding mechanism.
- **Rotating latch.** Folding starts by unlocking a rotating latch on the bottom rod, which frees the entire front wheel assembly to pivot to the side.
- **Guided handlebar rotation.** As the front wheel rotates outward, the handlebars automatically shift into a straight, forward-aligned position through a guided rotation system, so they never interfere with the fold.
- **Fold-over.** Once the front assembly is fully rotated, the front section folds over the rear half of the frame, giving a compact form that is easy to carry or store.
- **Materials.** Steel for the main frame for strength, durability, and ease of manufacturing. Rubber on the handlebar grips and contact points for comfort and control.
- **Design constraints.** Rider stability, clearance between folding parts, and minimal hardware drove the detail decisions.

## Repository contents

```
Initial Sketch.pdf              Hand-drawn concept sheet from the start of the project
Solidworks and Drawing Files/   SolidWorks parts, assemblies, and drawings
Videos/                         Prototype and mechanism demo videos
```

### SolidWorks files

Open `Folding Bike (final).SLDASM` for the complete bike. `Completed Handle bars11.SLDASM` is the handlebar sub-assembly.

| Sub-system | Part files | Drawings |
| --- | --- | --- |
| Frame | `FINAL FRAM PART`, `frame 1`, `frame 2`, `Bottom (3)` | `FINAL FRAM PART Finished Drawing`, `frame 1`, `frame 2`, `Bottom (3)` |
| Folding hinge | `Hinge`, `Screw Hinge` | `hinge`, `Screw Hinge` |
| Handlebars | `NewImprovedHandleBars`, `TOPHandleBarHolder`, `Gripps` | `NewImprovedHandleBars`, `TOPHandleBarHolder`, `GripsDrawingFinished`, `complete11` |
| Seat | `SEAT`, `Seat Clamp - with rectangle piece for mate` | `SEAT`, `Seat Clamp ... Finished Drawing` |
| Clamp hardware | `Clamp Lever`, `Clamp Washer`, `Bolt`, `Nuttt`, `Second NUTTt` | matching `... Finished Drawing` files |
| Wheels | `bbs rims`, `bbs rims back` | `bbs rims Finished Drawing`, `bbs rims back Finsihed Drawing` |
| Full bike | `Folding Bike (final).SLDASM` | `Folding Bike (final).SLDDRW` |

Files ending in `(SECOND ONE)` are the revised versions of that part used in the final assembly.

### Videos

- `rotating mechanism.MOV` / `rotating mechanism (1).MOV` – the latch and front-assembly rotation
- `IMG_3374` to `IMG_3378` – prototype build and folding sequence
- `IMG_6642.mp4`, `IMG_6643.mov` – additional demo footage

## Opening the models

The models were made in SolidWorks. Open the `.SLDASM` files with all part files in the same folder so the references resolve. Drawings (`.SLDDRW`) reference their part or assembly by name.
