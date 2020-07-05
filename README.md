# PaintIn2D-Program

Purpose: use OpenGL graphics primitives, how the event loop works, display vs world coordinate systems in 2D, and what role interactivity places a part with how the display functions.

Overall: Create your very own paint program. You will use Unity in 2D mode and OpenGL commands.

1) a) Draw a continuous line with the mouse. When click down the mouse must continuously draw until mouse button is lifted without gaps in the line. Hint: Check that if you draw fast that there are not gaps between one movement to the next. b) Additionally be able to erase with the mouse. Hint: If there is no “erase” drawing tool, how might you achieve this otherwise?

2) Be able to change size of brush (at least 3 sizes), color of brush (at least 3 different colors), and have at least 3 options of shape (filled in regions) {circular and square are required, choose one additional: triangle, polygon, etc.}. Use parameterization, sampling loops (ie circle), and 2D OpenGL Transformation commands for drawing. Note: Continuous lines do not need to be drawn with your optional shapes ie. they will act more like a stamp tool- but 2 points extra bonus if you do! Variation for 4010: You may use actual points for your shapes.

3) As a part of your project, you must have a toolbar on the side where you have drawn shapes/icons (these can be very simple) and you have identified this ‘pick’ region to execute your code when the mouse clicks in this area. You can create this using multiple viewports. Variation for 4010: You may use “keyboard” commands to swap out the brushes and colors (instead of the ‘toolbar’). If you do this, then at least set up one viewport. 
