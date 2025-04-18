# Issue: Add Zoom and Pan Controls

## Description
This issue proposes adding controls for zooming in and out of the simulation and panning around the canvas. This feature will enhance user interaction by allowing users to explore the simulation in more detail, especially when dealing with multiple bodies or complex interactions.

## Requirements
1. **Zoom Controls**:
   - Implement a zoom in and zoom out functionality that allows users to adjust the scale of the simulation.
   - The zoom level should be adjustable via buttons or a slider.
   - Ensure that the zooming does not distort the bodies or trails.

2. **Pan Controls**:
   - Add functionality to pan the view around the canvas.
   - Users should be able to click and drag to move the view, or use arrow keys for finer control.
   - Implement boundaries to prevent panning outside the simulation area.

3. **User Interface**:
   - Create intuitive buttons or controls for zooming and panning.
   - Ensure that the controls are responsive and accessible.

4. **Performance Considerations**:
   - Optimize the rendering process to handle zooming and panning smoothly without significant performance drops.

## Additional Notes
- Consider using a library or existing solution for handling zoom and pan if it simplifies the implementation.
- Ensure that the zoom and pan functionality integrates well with existing features, such as the merging and trail rendering.

## Acceptance Criteria
- Users can zoom in and out of the simulation using the provided controls.
- Users can pan the view around the canvas.
- The simulation remains visually consistent and performs well during zooming and panning actions.