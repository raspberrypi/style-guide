# Style Guide for Raspberry Pi learning resources

This is a reference guide to the formatting and style choices which should be made when producing Rapsberry Pi learning resources, and related worksheets. It should also be referred to in the case of worked examples or code produced for demonstration purposes, particularly in the Documentation repository.    

This guide should be used in conjunction with the main [Raspberry Pi Style Guide](https://github.com/raspberrypilearning/style-guide/blob/master/style-guide.md), which gives advice on preferred spellings, capitalisation, formatting of times and dates, and a range of other material. 


|Item |Format |Notes |   	
|---|---|---|
|Headings and subheadings|Sentence case: capital letter on first word only|Example: 'What next?'|
|Emphasis or new concept|Bold|Example: ‘Using an infinite loop to repeatedly check the status of the input pin is called **polling**.’ <br/><br/>Be sparing with the use of bold for emphasis: overuse can make the document look cluttered and confusing. Do **not** use italics for emphasis.|
|File name|Code|Example: ‘Save your file: we called ours `allseeingpi.py` but you can use a different name if you wish.’|   	
|URL|Code|In many instances, URLs can be presented neatly as hyperlinks, for example: 'Visit the [Raspberry Pi homepage](raspberrypi.org) for more information'. <br/><br/>Code formatting should be used in cases where typing the URL forms part of the resource. For example: ‘url = foo.com’|
|Keystroke|`<kbd></kbd>`|Example: ‘Press <kbd>Ctrl+S</kbd> to save your file, then <kbd>F5</kbd> to run it.’|
|Menu item or button|Bold|Example: 'Select **New File**', 'Click the **Add Extension** button.|
|Menu items inside Scratch window or Python shell|Bold|Example: **Costumes** tab.|
|Python element (e.g. library)|Code|Match upper case/lower case. Be careful about names of libraries versus names of classes. For example: ‘The `picamera` library contains the `PiCamera` class.’|
|Scratch sprites|Bold, use 'the' in front of a sprite's name|Example: ‘the **Nadia** sprite’ <br> This also applies where the Stage is being referred to as a coding element, equivalent to a sprite, e.g. “Select the **Stage** and click on the **Backdrops** tab.” 
|Scratch blocks|Code (use colour) or graphics (screenshots)|Example: ‘Drag and drop a `when this sprite clicked`{:class="block3events"} block.’, 'Learn how to use `Motion`{:class="block3motion"} blocks'|
|Scratch blocks menu|Code (use colour)|Example: `Looks`{:class="block3looks"} blocks menu <br> Do not use the term 'Blocks palette'.|
|Scratch keystrokes and values|Code or graphics (screenshots)|Example: ‘In a `say`{:class="block3looks"} block, enter the text `Hello!`.’, 'Set the **Size** to `150` (percent)'|
|Scratch screen areas|Initial capital letter|Example: ‘Drag the block to the Code area.’|
|GPIO pins|Bold|**GPIO 4** (not ‘GPIO pin 4’, ‘pin 4’, ‘Pin 4’ etc. as this may cause confusion with board numbering). <br/><br/>**3V3**, **5V**. <br/><br/>**GND** or ground, depending on context, e.g. ‘connect to the ground rail on a breadboard’, or ‘the ground pin is labelled as **GND** on the pinout diagram’. <br/><br/>Wiring diagrams may also be used, but ensure that any captions follow the Style Guide.|
|GPIO pin modes|Bold, Caps|**HIGH**, **LOW**.|
|GPIO pin signals|Bold, Caps|**ON**, **OFF**.|
|HAT pins or sockets|Bold|Example: **Motor 1 +**, **Input 1**.|
|Resistors|Bold|Example: **R1**, **R2** (example from [Fart Detector](https://www.raspberrypi.org/learning/fart-detector/) resource).|
|Words printed on a board (e.g. a HAT)|Bold|Example: **Servos**, **Input**, **Output**, **Motion**.|
|Explanations or notes|No formatting|Prefix with '**Note:**' if needed. Do not apply additional formatting (bold/italics/underlining).|
|Binary numbers|Bold/no formatting|Bold for emphasis if required for emphasis/clarity. Otherwise, do not apply additional formatting.|
|Attributions|Italics|Attributions should be italicised and made at the foot of the page, where necessary. See [the config.txt README](https://github.com/raspberrypi/documentation/tree/master/configuration/config-txt) in the Documentation repository for an example.|
|Collapsible section headings|Express text as string when necessary|E.g. `title: "Advanced: install Mu on Windows/macOS using pip"`, otherwise the colon will break the project|

## Scratch style guide

The notes below expand on the information in the table above.

### Interface locations and menus or menu items:
Bold, initial capital letter
This includes, for example:
+ **Costumes** tab
+ **Pen** extension (this is only when clicking on an extension in the Extensions Library — see below for references to the blocks menu)
+ Click the **Extensions** button
+ Click on **Convert to Bitmap**
+ Tool names, e.g. Click on the **Brush** tool
+ Click on the **Fill** colour chooser 
+ Set the **Size** to `150` (percent)
<br>This applies to locations/items you click on, in general, with the exception of blocks/blocks menus (see next section)

### For specific reference to a block or blocks menu, use colour:
+ `Motion`{:class="block3motion"} block
+ `Looks`{:class="block3looks"} blocks menu 
+ `Pen`{:class="block3extensions"} blocks menu 
+ **Note:** Don’t use the term ‘Blocks Palette’. 

### Scratch screen areas:
+ Stage — this is the Stage itself, which shows the output
+ Stage area — this includes the Stage and the buttons above it (e.g. green flag)
+ Stage pane — this is the pane that you click on to select the Stage and choose backdrops
+ Sprite pane — this is the pane directly below the Stage, which you use to change values about the sprite (Note: The values are also referred to as ‘properties’, e.g. “you can change the sprite’s properties”)
+ Sprite list — this is the area where you can see all of the sprites in the project and click on sprites to select them
+ Code area
+ Blocks menu 
+ Paint editor
+ **Note:** 'tab' refers to locations displayed like browser tabs, e.g. '**Code** tab' (these are classed as menu items inside the Scratch window, as above)

### Sprites:
+ Names in bold
+ Always use ‘the’ or The’ in front of a sprite name, e.g. ‘the **Basketball1** sprite’
+ This also applies where the Stage is being referred to as a coding element, equivalent to a sprite, e.g. “Select the **Stage** and click on the **Backdrops** tab.”

### Blocks, text, and keyboard keys:
+ All references to blocks should be stylised as in this example: `move`{:class="block3motion"}
+ This includes references to parts of blocks, e.g. “add a `go to x: y:`{:class="block3motion"} block with `x`{:class="block3motion"} set to `70` and `y`{:class="block3motion"} set to `-25`.”. 
+ This also includes references to variables (and similar), e.g. “The next step is to set the value of `repetitions`{:class="block3variables"}` when the program starts.”
+ Values should be in code (to indicate typing), e.g. “set to `70` and `y`{:class="block3motion"} set to `-25`.” 
+ In addition, all references to typing should also be in code (backticks), e.g. “type `breathe out` in the `say`{:class="block3looks"} block.”
+ All references to keyboard keys should be written between the tags <kbd></kbd>, e.g. “Press <kbd>Enter</kbd> or <kbd>+</kbd>.”
+ Where applicable, it is fine to refer to rounded blocks such as variables as ‘rounded blocks’
+ Where blocks include drop-down menus, write the block as you would read it, e.g. `broadcast message1 and wait`{:class="block3events"} block. The exception to this is when you are talking about one of these blocks in a context that is not an instruction, e.g. “In this project, you will learn how to use `broadcast`{:class="block3events"} blocks”
+ Operators blocks: It is ok to refer to operators blocks as ‘operators’ if you are explaining what they do, rather than referring to a specific block in an instruction, e.g. “You can use an `and`{:class="block3operators"} operator to test for two different conditions. Add an `and`{:class="block3operators"} block into the `repeat until`{:class="block3control"} block.”
+ `if … then … else`{:class="block3control"} block — note spaces
+ `say`{:class="block3looks"} block
+ `wait`{:class="block3control"} block
+ `wait until`{:class="block3control"} block
+ `set size to`{:class="block3looks"} block — do not include the value box or % sign, but depending on the context, write “(percent)” after the value, e.g. “add a `set size to`{:class="block3looks"} block and set the size to `50` (percent)”
+ `when green flag clicked`{:class="block3events"} block
+ `go to x: y:`{:class="block3motion"} block
+ `touching edge`{:class="block3sensing"} block — no question mark
+ `touching color`{:class="block3sensing"} block

### Other formatting notes:
+ Never use italics or underlining
+ For emphasis, use bold (but use sparingly)
+ Tips/notes should be stylised as in this example (i.e. “Tip:”/“Note:” in bold including colon, followed by a full sentence starting with a capital letter and ending with usual punctuation): **Tip:** Stamps go on top of the backdrop but underneath the sprites.
+ Use double quotation marks for speech (that has already been typed), e.g. Enter the text `Yes`. The sprite should reply, “That’s great to hear!”
+ True and false: There is no set formatting for the terms ‘true’ and ‘false’, because they are used in different ways and different blocks. For example: <br> If the user needs to type ‘true’ or ‘false’ in a block, use backticks, e.g. “Add blocks to `set`{:class="block3variables"} the `finished`{:class="block3variables"} variable to `false`”
<br> If it is an explanation of what a block does, and the terms are not used in the program/instruction, the terms do not need any additional formatting, e.g. “You can use an `if … then`{:class="block3control"} block to check if `finished`{:class="block3variables"} is true or false.”


### Other terms and phrases:
+ Lower case: sprite, studio, extension, extension block, script (a group of blocks joined together)
+ 'costume': lower-case for the "item"; upper-case and bold '**Costumes** tab' for the interface location name
+ In text refer to: “Click on the green flag”
+ “choose a sprite/costume from the Sprite Library/Costume Library”
+ Extension/extension block: ‘extension’ refers to the extension in general (e.g. “Explore the Scratch extension, `Video Sensing`{:class="block3extensions"}”) and ‘extension blocks’ refers to the blocks in the menu of that extension (e.g. “Make a movement detector using the Scratch `Video Sensing`{:class="block3extensions"} extension blocks.”)
