## Issue Title: Add Pause and Resume Functionality

### Description
This issue proposes adding functionality to pause and resume the simulation. Users should be able to stop the simulation temporarily and then continue from where they left off. This feature will enhance user experience by allowing users to take breaks, analyze the simulation state, or make adjustments without losing their progress.

### Requirements
- Implement a pause button that stops the simulation loop.
- Implement a resume button that continues the simulation from the paused state.
- Ensure that the current state of the simulation (positions, velocities, etc.) is preserved when paused.
- Update the UI to reflect the current state (paused or running).
- Consider adding keyboard shortcuts for quick access to pause and resume functionality.

### Additional Notes
- This feature could be particularly useful for educational purposes, allowing users to pause the simulation to better understand the interactions between bodies.
- Ensure that the pause and resume functionality does not interfere with other features, such as adding new bodies or changing parameters while paused.