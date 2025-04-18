# Title: Add Merging Feature for Bodies in the Simulation

## Description
This issue proposes implementing a merging feature for bodies in the simulation. When two bodies collide, they should merge into a single body, combining their mass and velocity, and interpolating their colors. This feature will enhance the realism of the simulation and provide users with a more engaging experience.

## Requirements
- Detect collisions between bodies in the simulation.
- Implement a merging algorithm that:
  - Combines the mass of the colliding bodies.
  - Calculates the new velocity based on the masses and velocities of the merged bodies.
  - Interpolates the colors of the merged bodies to create a visually appealing result.
- Ensure that the merged body is represented correctly in the simulation, including its position, velocity, and trail.

## Acceptance Criteria
- When two bodies collide, they merge into one body.
- The new body has a mass equal to the sum of the two original bodies.
- The new body's velocity is calculated based on the momentum of the original bodies.
- The color of the new body is a blend of the two original colors.
- The simulation continues to function correctly after merging, with the new body behaving as expected.

## Additional Notes
- Consider adding visual feedback for merging, such as a brief animation or effect.
- Ensure that the merging feature does not introduce performance issues in the simulation.