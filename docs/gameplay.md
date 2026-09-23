## Gameplay

The core interaction is simple: drag and drop components and wires to build a circuit.

- The game has two modes: **Design Mode** and **Play Mode**.
- In Design Mode, the player assembles, moves, and connects components without powering the circuit.
- A clearly labeled **Power** button switches the circuit into Play Mode and powers the current design.
- Play Mode shows the circuit's behavior and consequences; the player can reset it and return to Design Mode to try another arrangement.
- Components and wire endpoints snap to an underlying grid to keep the board neat. The grid need not be visible; for example, a component dragged to `(42, 83)` snaps to `(40, 80)`.

- Connecting a wire to a battery by itself does nothing.
- Incomplete or harmless circuits remain unchanged.
- The player must power a circuit to see its result.
- Unsafe setups produce a clear, visible consequence when powered.

For example, powering a `battery → wire → LED → wire → battery` circuit should immediately overload the LED, causing it to explode or display another obvious failure effect. The player should then be able to reset the circuit and try a different arrangement.

Changing a circuit should be quick and encourage experimentation:

- The player turns the circuit off, changes component values or arrangement, then powers it again to see the result.
- Component values can be adjusted directly in the play area with a simple interaction, without dialogs or confirmation steps.
- For example, a circuit with a 10-ohm resistor produces a proportionally bright LED; increasing the resistance and powering the circuit again makes the LED visibly proportionally dimmer.
- Editing remains primarily drag-and-drop (or similarly direct), and components cannot be changed while the circuit is powered.

