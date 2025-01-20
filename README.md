# Expo Camera Preview Freeze with Custom Controls

This repository demonstrates a bug in the Expo Camera API where the preview freezes when using manual camera controls.  The issue is more likely to occur on lower-end devices or when intensive custom controls are implemented.

The `cameraBug.js` file shows the problematic code. `cameraBugSolution.js` demonstrates a solution using careful state management and error handling.

## Steps to Reproduce
1. Clone this repository.
2. Run `expo start`.
3. Observe the camera preview.  The preview may freeze after some time, especially with active adjustments to focus or zoom. 
4. Try the solution in `cameraBugSolution.js` which involves adding more robust error handling and state management.