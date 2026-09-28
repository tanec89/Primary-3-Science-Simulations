# Primary 3 Science Simulations

Interactive browser-based simulations for Primary 3 science topics. Each simulation is a self-contained HTML file — just open it in a browser, no installation needed.

## Simulations

### Magnets — Magnetising a Nail (`Magnets/magnetisation.html`)

Demonstrates the **stroking method** of magnetising a steel nail with a bar magnet.

- Drag the magnet's tip across the nail from head to tip (or tip to head) to stroke it. Each full stroke increases the nail's magnet strength, tracked by a stroke counter and a strength meter.
- Stroking must stay in a **consistent direction** — reversing direction (or flipping the magnet) fights the polarity already built up and drains the nail's strength instead of adding to it.
- Flip the magnet's poles with the **Flip Magnet** button to see how the touching pole determines which end of the nail becomes north or south.
- As the nail magnetises, its ends visibly take on colour (red/blue) to show polarity, and it attracts more paper clips (up to 10), following a diminishing-returns curve rather than a straight line.
- Leave the nail alone and its magnetism gradually decays over time, illustrating that this type of magnetism isn't permanent.
- **Quick Test** buttons jump straight to 10, 50, or 100 strokes to skip ahead and see the end states.
- **Reset** returns the nail and magnet to their starting state.

### Magnet Detective (`Magnets/magnet-detective.html`)

A mystery/quiz game where you use a test magnet to identify three unlabelled bars — each is randomly either a **non-magnetic material**, a **magnetic material**, or a **magnet**.

- Drag the magnet onto each end of Bar A, B, and C to test it: it gets pulled in (attracts), pushed away (repels), or nothing happens.
- **Flip Magnet** swaps which pole faces outward, so you can test with either pole — but the game reminds you to keep it consistent across both ends of the same bar, just like a real magnet.
- The behaviour follows real magnetism rules: non-magnetic materials never attract; magnetic materials (like iron) always attract to either pole; a real magnet attracts on one end and repels on the other (like poles repel, unlike poles attract).
- Once all six ends are tested, a quiz appears asking you to classify each bar as a magnet, magnetic material, or non-magnetic material, with instant feedback and a score.
- **New shuffle** / **Play again** randomises the three bars' identities and poles for a fresh round.

### Electromagnet Lab (`Magnets/electromagnet_lab.html`)

An interactive circuit diagram exploring how an **electromagnet's** strength depends on the number of coils and batteries.

- Drag the **coils** and **batteries** sliders (1–20 coils, 1–10 batteries) to redraw the circuit live: more coil loops wind around the iron rod, and more battery cells are added to the pack.
- The number of paper clips attracted (up to 18) updates instantly, with a "current flowing" animation along the wire.
- **Enable Data Logger** records each trial's coil count, battery count, and clips attracted into a results table, mirroring how a real experiment's readings would be logged.
- **Pause** stops the current-flow animation; **Reset Setup** returns the sliders to their defaults; **Reset Table** clears the logged trials.

## Usage

Open any simulation's `.html` file directly in a web browser — no server or build step required.
