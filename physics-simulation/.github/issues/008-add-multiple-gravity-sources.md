## Issue Title: Add Multiple Gravity Sources

### Description
This issue suggests allowing the addition of multiple gravity sources in the simulation. Currently, the simulation only accounts for gravitational interactions between bodies. By implementing multiple gravity sources, users will be able to create more complex gravitational interactions, such as simulating the effects of multiple stars or planets on a body.

### Proposed Features
1. **User Interface**: 
   - Add a section in the controls to allow users to define multiple gravity sources, including their positions, masses, and colors.
   - Provide an option to add or remove gravity sources dynamically during the simulation.

2. **Gravity Calculation**:
   - Modify the gravitational force calculation in the simulation to account for all defined gravity sources.
   - Ensure that the gravitational influence of each source is computed correctly based on its mass and distance from the affected bodies.

3. **Visual Representation**:
   - Draw the gravity sources on the canvas, allowing users to see where the gravitational influences are coming from.
   - Use distinct colors or shapes to differentiate between various gravity sources.

4. **Documentation**:
   - Update the project documentation to include instructions on how to use the multiple gravity sources feature, including examples of different configurations.

### Benefits
- Enhances the educational value of the simulation by allowing users to explore complex gravitational interactions.
- Provides a more realistic simulation environment for users interested in astrophysics or orbital mechanics.
- Increases user engagement by allowing for more creative experimentation with the simulation.

### Additional Notes
- Consider the performance implications of adding multiple gravity sources, especially in terms of rendering and calculations.
- Ensure that the user interface remains intuitive and does not overwhelm users with too many options.