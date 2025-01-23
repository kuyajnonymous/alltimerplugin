This PowerShell script creates a small, interactive GUI that displays different messages based on the connection status of a mouse. The GUI window is black with a label that shows either "FREE PLAY" or "INSERT COIN" depending on whether a mouse is detected on the system.

### Features:
1. **No Border Window**: The form has no window border, and it stays on top of other windows.
2. **Dynamic Background**: 
   - If a mouse is detected, the form's background will remain black, and the label will display "FREE PLAY".
   - If no mouse is connected, the form covers the entire screen with a black background, and the label will display "INSERT COIN".
3. **Mouse Interaction**: The label can be dragged around the screen.
4. **Mouse Detection**: The script continuously checks the system for mouse connectivity every second. If the mouse is disconnected, the screen display changes to indicate the need for an action (like inserting a coin).

### How to Use:
- **Prerequisites**: Windows operating system with PowerShell.
- **Run the Script**: Paste the script into a PowerShell window or save it as a `.ps1` file and execute it in PowerShell.
- The form will appear showing
