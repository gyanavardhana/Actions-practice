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


# Rich Internet Applications (RIAs) with Flex 3

## Introduction to Flex 3

- **Adobe Flex 3** is a development framework used to build RIAs. 
- It provides developers with tools to create highly interactive applications that can run in web browsers using the Adobe Flash Player runtime or as standalone applications using Adobe AIR.
- Although Flex was popular in the mid-2000s, the evolution of web technologies like HTML5, CSS3, and JavaScript frameworks has largely replaced it in modern web development.

## Key Features of Flex 3

- **Rich User Interfaces:** Flex 3 offers pre-built components (like buttons, sliders, data grids, and charts) for creating dynamic and visually appealing user interfaces. It also supports skinning and styling for customising the application's look and feel.
- **MXML for Declarative Programming:** Flex applications are built using **MXML**, an XML-based markup language, to define UI elements in a declarative way. It allows developers to focus on the application's layout and design while integrating seamlessly with ActionScript for handling the logic.
- **ActionScript 3.0 Integration:** ActionScript 3.0 is the core programming language for Flex applications. It provides a robust object-oriented programming environment for creating application logic.
- **Data Connectivity:** Flex 3 includes data services for connecting to remote backends via protocols like HTTP, SOAP, and AMF (Action Message Format). It simplifies working with XML, REST APIs, and server-side technologies like Java, .NET, and PHP.
- **Flex Charting:** The Flex Charting package allows developers to create interactive charts, graphs, and dashboards for data visualisation, which is useful for business and analytical applications.
- **Cross-Platform and AIR Support:** Flex 3 applications can run in any modern browser with Flash Player or as desktop applications using Adobe AIR, ensuring cross-platform compatibility.
- **Development Environment:** Adobe Flex Builder 3, an Eclipse-based IDE, provides tools for debugging, profiling, and visual design, enhancing developer productivity.
- **Open Source:** Adobe Flex 3 was released as an open-source project.

## Use Cases for Flex 3

- **Enterprise Applications:**  Dashboards, data-driven apps, and CRMs
- **Media and Entertainment:** Interactive websites, video players, and rich multimedia experiences
- **E-commerce:** Product configurators, shopping carts, and engaging storefronts

## Developing with Flex 3

Developing with Adobe Flex 3 involves using its framework and tools to create RIAs. Flex 3 applications are built using a combination of MXML (for UI design) and ActionScript 3.0 (for application logic).

### 1. Set Up the Development Environment

- **Install Adobe Flex SDK 3:** This is the core framework needed to compile and run Flex applications.
- **Use an IDE:**
  * **Adobe Flex Builder 3:** This is an Eclipse-based IDE optimised for Flex development. It includes features like visual layout design, debugging tools, and code assistance.
  * Alternatively, you can use any text editor and compile using the command-line compiler (mxmlc) included in the SDK.
- **Install Flash Player:**  Ensure you have a compatible version of Flash Player for testing applications in the browser.

### 2. Understand the Core Languages

- **MXML (Markup Language):**
  * Used for defining the application's UI in a declarative way.
- **ActionScript 3.0:**
  * A robust, object-oriented language for handling application logic.
  * You can embed ActionScript in MXML or define it in separate files.

### 3. Develop Your First Flex Application

- Create a new project in Flex Builder or set up a folder structure manually.
- Write your UI components in an MXML file (e.g., Main.mxml).
- Implement application logic in embedded or external ActionScript files.

## Working with Components in Flex 3

Components are the building blocks of your application in Adobe Flex 3. They can be visual (e.g., buttons, labels) or non-visual (e.g., services, validators), and you can use pre-built components provided by the framework or create custom ones.

### 1. Types of Components

- **Built-in Components:**
  * Flex provides a rich set of pre-defined components in the mx.* namespace.
- **Custom Components:**
  * You can create reusable components by extending existing ones or building entirely new ones, which is useful for modular and maintainable code.

### 2. Using Built-in Components

To use components in your Flex application, declare them in MXML or instantiate them in ActionScript.

### 3. Custom Components

- **Creating Custom Components:**
  * A custom component is typically defined as a separate MXML file or an ActionScript class.
- **Extending Components in ActionScript:**
  * You can extend existing components to add new functionality.

### 4. Layout and Containers

Flex components are typically placed inside layout containers, which control their arrangement.

- **Horizontal Layout:** Use HBox to arrange components horizontally.
- **Vertical Layout:** Use VBox to stack components vertically.
- **Absolute Positioning:** Use Canvas for precise control over placement.

### 5. Styling and Skinning Components

- **Styling with CSS:**
  * You can define styles for components in an external or embedded CSS file.
- **Skinning Components:**
  * You can create custom skins to completely change the appearance of components, often using graphic design tools or Flex's drawing APIs.

### 6. Binding Data to Components

Flex supports data binding, allowing components to automatically update when the underlying data changes.

### 7. Handling Events

Components in Flex 3 dispatch events for interaction. You can handle these events using ActionScript.

### 8. Component Life Cycle

Flex components follow a life cycle:

- **Creation:** The component is instantiated.
- **Initialisation:** Properties are set and children are added.
- **Layout:** Sizes and positions are calculated.
- **Rendering:** The component is displayed on the screen.

You can override these methods for custom behavior:

- createChildren(): Add child components.
- updateDisplayList(): Adjust layout and drawing.

### 9. Reusable Component Patterns

To build scalable applications:

- Use custom components for repetitive UI.
- Separate logic into ActionScript classes or utilities.
- Use Modules for lazy loading of heavy components.

## Advanced Component Development in Flex 3

Advanced component development in Flex 3 involves creating custom, dynamic, and reusable components with enhanced functionality.

### 1. Custom Components

- **MXML-Based Components:** These components are built using MXML and can include ActionScript for custom logic.
- **ActionScript-Based Components:** These components provide more control and are built entirely in ActionScript. They are ideal for creating non-visual or highly dynamic components.

### 2. Component Life Cycle

Understanding and overriding the component life cycle methods allow you to control how your components are created and rendered. 

Key methods include:

- createChildren(): Called during initialisation to add child components.
- commitProperties(): Used to commit property changes.
- measure(): Sets component dimensions.
- updateDisplayList(): Handles layout and visual rendering.

### 3. Skinning and Styling

- **Custom Skins:** You can use graphical tools (like Adobe Flash or Illustrator) or Flex drawing APIs to create unique skins for components.
- **CSS Styling:** CSS allows centralised control over component appearance. You can define reusable styles.

### 4. Data-Driven Components

Data-driven components dynamically render UI elements based on data sources such as ArrayCollection or custom data providers.

### 5. Component Communication

- **Custom Events:** Custom events allow components to communicate effectively.
- **Parent-Child Communication:** Pass references or use event bubbling for communication.

### 6. Performance Optimisation

- Use Validation: Use methods like invalidateProperties(), invalidateSize(), and invalidateDisplayList() to defer expensive calculations until necessary.
- Minimise Repainting: Group updates to avoid frequent rendering.
- Lazy Loading: Load heavy components or modules only when needed.

### 7. Modular Development

Split large applications into modules to improve maintainability and performance. Use the ModuleLoader component to load modules dynamically.

### 8. Reusable Patterns

- **Component Composition:** Combine smaller components into a larger reusable component.
- **Dependency Injection:** Use dependency injection frameworks like Cairngorm or PureMVC for advanced architecture.

### 9. Accessibility

Ensure components are accessible by providing:

- Tooltips
- Keyboard Navigation
- ARIA Support (using accessibilityImplementation)

### 10. Testing and Debugging

Use tools like FlexUnit for unit testing and Flex Builder Debugger for debugging components. Focus on testing:

- Component states
- Event handling
- Data bindings

## Visual Effects and Multimedia in Flex 3

Visual effects and multimedia in Flex 3 allow developers to create dynamic and visually appealing user interfaces.

### 1. Visual Effects in Flex 3

Flex 3 provides built-in effects and transitions to enhance user interaction.

- **Built-in Effects:** Some common built-in effects include:
  * Fade: Gradually changes the opacity of a component.
  * Move: Moves a component from one position to another.
  * Resize: Changes the width and/or height of a component.
  * Rotate: Rotates a component.
  * Zoom: Changes the scale of a component.
- **Triggering Effects:** Effects can be triggered by:
  * Events: e.g., click, mouseOver, etc.
  * Effect Triggers: showEffect, hideEffect, creationCompleteEffect
- **Custom Effects:** You can create custom effects by extending the Effect class or using ActionScript.

### 2. Transitions

Transitions are animations that play when a component changes state. They are defined in the `<transitions>` block and triggered automatically when switching states.

### 3. Multimedia in Flex 3

Flex 3 supports multimedia elements such as images, video, and audio to create rich applications.

- **Displaying Images:** Use the `<Image>` component to load and display images.
- **Embedding Multimedia Assets:** Assets can be embedded directly in your application using the @Embed directive.
- **Playing Audio:** Flex 3 supports playing audio using the Sound class in ActionScript.
- **Playing Video:** Flex 3 provides the `<VideoDisplay>` component to play video files.
- **Handling Multimedia Events:** You can handle events like complete, progress, or ioError for multimedia components.

### 4. Filters and Effects

Filters add graphical effects to components, such as shadows, blurs, and glows.

- **Applying Filters:** Filters are applied using the filters property of a component.

### 5. Dynamic Graphics with ActionScript

Flex allows you to create dynamic graphics using the Graphics class.

### 6. Integration with Flash

Flex 3 integrates seamlessly with Flash assets, enabling developers to use Flash animations, vector graphics, or SWF files within applications.

### 7. Best Practices for Multimedia

- Optimise Assets: Compress images, audio, and video to reduce loading time.
- Preload Resources: Use the ProgressBar component to show load progress.
- Fallback Content: Provide alternative content if multimedia fails to load.
- Accessibility: Ensure multimedia elements are accessible (e.g., subtitles for videos, alt text for images).

By combining visual effects, transitions, and multimedia features, Flex 3 enables developers to build engaging and interactive user experiences for web and desktop applications.
