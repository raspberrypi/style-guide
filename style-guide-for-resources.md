# Style Guide for Raspberry Pi learning resources

A reference guide to the formatting and style choices which should be made when producing learning resources. 

This guide should be used in conjunction with the main [Raspberry Pi Style Guide](https://github.com/raspberrypilearning/style-guide/style-guide.md), which gives advice on preferred spellings, capitalisation, formatting of times and dates, and a range of other material. 


|Item |Format |Notes |   	
|---|---|---|
|Emphasis or new concept|Bold|Example: ‘Using an infinite loop to repeatedly check the status of the input pin is called **polling**.’ <br/><br/>Be sparing with the use of bold for emphasis: overuse can make the document look cluttered and confusing. Do **not** use italics for emphasis.|
|Filename|Code|Example: ‘Save your file: we called ours `allseeingpi.py` but you can use a different name if you wish.’|   	
|URL|Code|In many instances, URLs can be presented neatly as hyperlinks, for example: 'Visit the [Raspberry Pi homepage](raspberrypi.org) for more information'. <br/><br/>Code formatting should be used in cases where typing the URL forms part of the resource. For example: ‘url = foo.com’|
|Keystroke|Code|Example: ‘Press `Ctrl+S` to save your file, then `F5` to run it.’|
|Menu item|Bold|Example: 'Select **New File**'.|
|Menu items inside Scratch window or Python shell|Bold|Example: **Costumes**, **Motion** blocks.|
|Python element (e.g. library)|Code|Match upper case/lower case. Be careful about names of libraries versus names of classes. For example: ‘The `picamera` library contains the `PiCamera` class.’|
|Scratch blocks|Code or graphics (screenshots)|Example: ‘Drag and drop a `when this sprite clicked` block.’|
|Scratch keystrokes|Code or graphics (screenshots)|Example: ‘In a `say` block, enter the text `Hello!`.’|
|Scratch screen areas|Initial capital letter|Example: ‘Drag the block to the Scripts area.’|
|GPIO pins|Bold|**GPIO 4** (not ‘GPIO pin 4’, ‘pin 4’, ‘Pin 4’ etc. as this may cause confusion with board numbering). <br/><br/>**3V3**, **5V**. <br/><br/>**GND** or ground, depending on context, e.g. ‘connect to the ground rail on a breadboard’, or ‘the ground pin is labelled as **GND** on the pinout diagram’. <br/><br/>Wiring diagrams may also be used, but ensure that any captions follow the Style Guide.|
|GPIO pin modes|Bold, Caps|**HIGH**, **LOW**.|
|GPIO pin signals|Bold, Caps|**ON**, **OFF**.|
|HAT pins or sockets|Bold|Example: **Motor 1 +**, **Input 1**.|
|Resistors|Bold|Example: **R1**, **R2** (example from Fart Detector resource).|
|Words printed on a board (e.g. a HAT)|Bold|Example: Servos, Input, Output, Motion.|
|Explanations or notes|No formatting|Prefix with '**Note:**' if needed. Do not apply additional formatting (bold/italics/underlining).|
|Binary numbers|Bold/no formatting|Bold for emphasis if required for emphasis/clarity. Otherwise, do not apply additional formatting.|


