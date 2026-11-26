# Hamtramck Sanborn map 1949-1951: window 1 viewer (work in progress)

An offline map viewer for one area ("window 1") of the 1949-1951 Sanborn fire-insurance map of Hamtramck, Michigan, with a **draft building layer**. It has not been checked by people. Treat it as a starting point for students to correct.

## How to open
1. Download this repository (green **Code** button, then **Download ZIP**) and unzip it, or clone it.
2. Double-click `index.html` (Chrome or Edge). No internet and no server are needed.

## What you see
- The old map; zoom in far enough and the sharp level-20 tiles replace the soft map.
- **Draft outlines** and **centroid points**, one per building, as two separate layers.
- **House numbers** read from the sharp Library of Congress sheets and the sharp map tiles, and a **draft street** (nearest OpenStreetMap street line).
- A material guess (from the fill colour).
- Optional: the **hand-made buildings** from the Michigan Tech project, to compare with the draft.
- **Review mode** (tick it in the left panel): students can correct a building's house number or street, mark it right or wrong, add a missing building, and download their corrections as a CSV. Corrections are saved in the reader's own browser.
- Click a building for its details. "(check)" means the draft is unsure.

## How good is it? (window 1, compared with the hand-made buildings)
- Finds about two thirds of the hand-made buildings (centre point within 5 m).
- A house number, when given, is right about three times in four; many buildings have no number yet.
- The draft street is right about nine times in ten for the buildings checked; some buildings on Joseph Campau get a side street.

## Credits
- Map tiles and hand-made building outlines: Michigan Tech, Hamtramck Historic Spatial Archaeology Project (clipped and rectified by Dan Trepal, 2023).
- Original Sanborn Fire Insurance maps: Library of Congress.
- Street lines: (c) OpenStreetMap contributors (ODbL).

No pupil data is in this repository. Draft layer: work in progress.


