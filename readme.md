# **Piratage Multitool V0.0.B-PreRelease**
## **⚠️⚠️⚠️ Disclaimer ⚠️⚠️⚠️**
The purpose of this program is solely for educational purposes. This program is not intended for any commercial or malicious purposes, and its use is at the user's own risk. By using this program, the user acknowledges and agrees that the creator of the program assumes no responsibility for any damages or losses that may result from the use of this program. It is the user's responsibility to use this program only for lawful and ethical purposes and to comply with all applicable laws and regulations. The creator of the program disclaims any and all liability arising from the use of this program and makes no warranties, express or implied, including but not limited to warranties of merchantability and fitness for a particular purpose. The user assumes all responsibility and risk for the use of this program and agrees to hold harmless the creator of the program from any claims, damages, or liabilities that may arise from the use of this program.

# Piratage Custom Programs
Piratage Custom Programs offer an extension to the Piratage platform. These programs are designed to be customized according to your specific needs and are written in Lua, a programming language known for its flexibility and ease of use. By using Piratage Custom Programs, you can enhance the functionality of Piratage and tailor it to your specific requirements. With the ability to create custom scripts, you can automate repetitive tasks, integrate with external systems, and add new features to Piratage that are not available out of the box. 

## Documentation ⚠️ Experimental ⚠️

### Getting Started
You need at least VIP permissions to create and execute custom programs.

First open the 'Custom Program Writer'.
Then go to 'File' and click 'New'.
The 'Entry.lua' file is the entry point of your program, so don't delete it.
Open the Entry.lua file.
You are ready to code!

### Global Functions
``` print(value) ```
Prints 'value' to the console.
**(value)** The value to print.

``` println(value) ```
Prints 'value' to the console with new line.
**(value)** The value to print.

``` read() ```
Reads a single character from the console.
**Returns:**
**(value)** The character pressed.

``` readln() ```
Reads a line from the console.
**Returns:**
**(value)** The line written.

``` clear() ```
Clears the console.

``` setCursorPos(left, top) ```
Sets the cursor position to the given position.
**(left)** The cursor left position.
**(top)** The cursor top position.

``` getCursorPos() ```
Gets the current cursor position
**Returns:**
**(left, top)** The current cursor position.

``` beep() ```
Makes the console beep.

``` setForeground(color) ```
Sets the console foreground color
**(color)** A number between 0 and 15.

``` setBackground(color) ```
Sets the console background color
**(color)** A number between 0 and 15.

``` callFile(name) ```
Calls a Lua File and executes it.
**(name)** The name of the file.

``` readFile(path) ```
Reads a file.
**(path)** The path to the file.
**Returns:**
**(value)** The content of the file.

``` writeFile(path, content) ```
Writes to a file.
**(path)** The path to the file.
**(content)** The content to write to the file.