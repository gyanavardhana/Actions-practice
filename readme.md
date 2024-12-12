# Rich Internet Applications with Adobe Flash

## Introduction to Adobe Flash

Adobe Flash CS3 (Creative Suite 3) is a software used to create interactive and animated movies. It is used for a variety of purposes, including:

- Web-based banner advertisements
- Interactive websites
- Games
- Web-based applications with graphics and multimedia effects

Flash provides tools for:
- Drawing graphics
- Generating animations
- Adding sound and video

Flash movies can be:
- Embedded in web pages
- Distributed on CDs and DVDs as independent applications
- Converted into stand-alone, executable programs

Flash uses ActionScript 3.0, a scripting language similar to JavaScript, for interactive applications.

**Note:** To play Flash movies, the Flash Player plug-in must be installed in the web browser.

## Flash Movie Development

### Setting up a New Flash Document

1. Open Adobe Flash CS3.
2. Click "Flash File (ActionScript 3.0)" under the "Create New" heading on the welcome screen.
3. Save the new file with a meaningful name and the `.fla` extension.

### Understanding the Flash Development Environment

- **Movie Stage:** The white area where you place graphic elements.
- **Timeline:** Represents the movie's duration and is divided into frames.
- **Frames:** Represent moments in time within the movie.
- **Playhead:** Indicates the current frame.
- **Tools Bar:** Located on the left side of the environment, it contains tools for selecting, adding, removing, and manipulating graphics.
- **Panels:** Application windows that organise commonly used movie options.
- **Properties Panel:** Displays information about the selected object and allows property modification.

### Configuring Document Properties

1. Right-click the stage and select "Document Properties...".
2. Configure the following settings:
   - **Frame Rate:** Sets the speed at which frames are displayed (measured in frames per second - fps). The default is 12 fps.
   - **Background Color:** Determines the colour of the stage.
   - **Dimensions:** Define the width and height of the movie.

### Working with the Stage

- **Zoom Tool:** Allows you to enlarge or reduce the view of the stage.
- **Hand Tool:** Used to pan the stage.

### Creating a Shape

1. Select the desired shape tool (e.g., Oval Tool).
2. Set the Stroke color (outline) and Fill color using the swatches in the Colors section.
3. Click and drag on the stage to create the shape.
   - Hold down the Shift key while dragging to constrain proportions (e.g. create a circle with the Oval Tool).

### Understanding Keyframes

- **Keyframes:** Points of change in a Flash movie, indicated by a dot in the timeline.
- A keyframe is automatically created when you draw a shape in an empty frame.

### Modifying a Shape

1. Select the shape using the Selection Tool.
2. Use the Properties Panel to adjust the following:
   - Width and Height
   - Fill color (including gradient fills)

### Adding Text to a Button

1. Select the Text Tool.
2. Click on the stage where you want the text to appear.
3. Type the text.
4. Use the Properties Panel to adjust:
   - Font
   - Text size
   - Font weight (e.g. bold)
   - Font colour

### Converting a Shape into a Symbol

1. Select all the elements of the shape (e.g. fill, stroke, text) using the Selection Tool.
2. Select "Convert to Symbol..." from the Modify menu or press F8.
3. In the "Convert to Symbol" dialog:
   - Give the symbol a unique name.
   - Choose the Behavior:
     * Movie clip: For recurring animations
     * Button: For interactive buttons with actions like rollovers
     * Graphic: For static images and basic animations

### Editing Button Symbols

1. Double-click the button symbol's icon in the Library panel.
2. This opens the symbol's editing stage, which has four frames representing button states:
   - Up: The default state
   - Over: When the mouse hovers over the button
   - Down: When the button is pressed
   - Hit: Defines the active area of the button (not visible to the viewer)

### Adding Keyframes

1. Right-click on the desired frame (e.g., the Over frame for a rollover effect)
2. Select "Insert Keyframe" from the menu or press F6.

### Publishing Your Flash Movie

1. Select "Publish Settings..." from the File menu.
2. Choose the desired publishing formats (e.g. Flash, HTML, Windows Projector).
3. Click "Publish" to create the published files.
4. Copy the necessary files (e.g. HTML, JavaScript, SWF) to your web server.

## Creating Special Effects with Flash

### Importing and Manipulating Bitmaps

1. Select "File > Import > Import to Stage..." or press Ctrl-R.
2. Browse to the image file and click "OK".
3. Convert imported images into editable shapes by selecting the image and pressing Ctrl-B or choosing "Break Apart" from the Modify menu.
4. Use editing tools to manipulate the imported image:
   - Lasso Tool: Selects areas of shapes
   - Paint Bucket Tool: Fills selected areas with colour
   - Eraser Tool: Removes shape areas
   - Brush Tool: Applies colour to shape areas

### Creating an Advertisement Banner with Masking

1. Create a new Flash document with the desired dimensions.
2. Create three layers: top, middle, and bottom.
   - Top Layer: Contains the mask
   - Middle Layer: Contains the masked animation
   - Bottom Layer: Contains a background image or other elements

### Adding Online Help to Forms

- This section combines techniques like tweening, masking, importing sounds and images, and ActionScript.
- The example describes creating an online form with interactive help using animations triggered by buttons next to form fields.
- The process involves using movie clips for animations, stop actions to control playback, and frame labels to navigate to specific frames.

### Creating a Website Splash Screen

- **Splash Screen/Preloader:** A simple animation that plays while a web page loads.
- The example describes creating a splash screen with a loading animation that pauses until all movie elements are loaded.
- Steps involve:
  * Creating animated movie clip symbols for preloaded objects
  * Using motion tweening to create animations
  * Adding ActionScript to control playback and loading

## ActionScript 3.0

- ActionScript 3.0 is Flash's scripting language for creating interactive elements and complex functionality.
- Figure 14.53 in the source document lists common ActionScript 3.0 functions.

## Web Sources

- Download Adobe Flash CS3 trial version: [www.adobe.com/products/flash/](http://www.adobe.com/products/flash/)
- Download the latest Flash Player plug-in: [www.adobe.com/go/getflashplayer](http://www.adobe.com/go/getflashplayer)
- Download the Flash Player Detection Kit: [www.adobe.com/products/flashplayer/download/detection_kit/](http://www.adobe.com/products/flashplayer/download/detection_kit/)
