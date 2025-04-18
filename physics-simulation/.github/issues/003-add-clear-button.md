## Issue Title: Add Clear Button

### Description
This issue requests the addition of a clear button that resets the simulation, removing all bodies and trails. This feature will allow users to start fresh without needing to reload the page, enhancing the usability of the simulation.

### Proposed Implementation
1. **Button Creation**: Add a "Clear" button to the controls section of the HTML file.
2. **Functionality**: Implement a function in `simulation.js` that clears all bodies from the `bodies` array and resets any relevant state variables.
3. **User Feedback**: Optionally, provide a confirmation dialog to prevent accidental clearing of the simulation.

### Steps to Implement
- Modify the `index.html` file to include a new button in the controls section.
- In `simulation.js`, create a function called `clearSimulation` that:
  - Empties the `bodies` array.
  - Resets any other necessary variables (e.g., trails, preview bodies).
  - Calls the `draw` function to refresh the canvas.
- Connect the button to the `clearSimulation` function using an event listener.

### Additional Notes
- Ensure that the button is styled consistently with the existing controls.
- Consider adding a tooltip or label to inform users about the button's functionality.