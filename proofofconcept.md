#Electric Playground Proof of Concept

##What goes into the PoC for Electric Playground?

**Most basic**
---
1. Creation of a circuit
- Battery
- Wire
- Resistor
- LED

2. What should happen?
- leaving out the resistor - the LED should "explode" (specific definition to be determined)
- introducing low resistance - the LED should shine bright
- increasing the resistance should decrease the brightness of the LED (just like real life)
- the player should "see" the electricity moving through the circuit, understanding the flow intuitively

3. Player Interaction
- Creating and editing the circuit should be largely intuitive, with only minor further explanation needed if any
- Changing variables (example - resistor value) should be done in a simple manner, so as to not distract from gameplay or usage.
- Resetting the game field should be trivial.  The inspiration for Electric Playground is chemistry sandboxes - resetting the game field should be as easy as dumping a beaker.
- Simulation should only be allowed when all steps are completed to close the circuit, without regard of the "safety" of the circuit.  Battery-resistor-led-battery is ok.  Battery-led-battery is ok (although it will destroy the led).  Battery-resistor-led is not ok, as the circuit is not completed.
4. Success
- The PoC is considered successful if someone who has no knowledge of the topic can understand why changing the resistor changes the brightness of the LED, the concept of electricity flowing through a circuit, etc
- The goal is conceptual understanding, not total understanding.  If the player can honestly say they understand it, they don't need to be able to teach it to someone else.  For the sake of the PoC, the goal is presenting the concept(s) in an easy to grasp manner.
- Engaging in these activities should be comfortable and native enough that the player will want to change the circuit.  What about increasing resistance?  decreasing resistance?  multiple LEDs? (multiple LEDs are not necessary for PoC implementation, only included here as an example of what the player could consider.)  The player should be able to grasp this enough that they want to, and feel comfortable with, changing the circuit to see what happens.  Success is, in part, inspiring the player to continue tweaking the circuit (changing the resistance, adding/removing LEDs, etc) to satisfy their curiosity.
- There's a saying that many great discoveries have started with someone saying "oh, that's weird..."  Success here, at this stage, can be looked at the same way.  If the player does X, and Y happens, and they're curious about why/how it happened and they're inspired to experiment further, that qualifies as success.