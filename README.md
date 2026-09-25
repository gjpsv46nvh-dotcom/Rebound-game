# REBOUND v34 – iPhone Start Adventure Fix
This version fixes the Home Screen Start Adventure issue at the touch layer.

Key fixes:
- The rotate-to-landscape overlay can no longer intercept taps.
- Portrait mode is no longer blocked by a full-screen rotate layer.
- Start Adventure responds to click, pointer-up and touch-end.
- Start screen and level controls are forced above the canvas.
- Removed manifest orientation restriction during iPhone Home Screen launch.
- Landscape still works and the game resizes when rotated.

After deployment, test the live website in Safari first. Then remove the old Home Screen icon and add the site again.
