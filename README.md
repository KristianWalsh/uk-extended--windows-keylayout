# UK (Extended) Windows keyboard layout

This is a key layout file to provide Windows users using UK keyboards with access to the same set of dead-keys and accents as Apple’s Unicode Extended keyboard layout.

This file does _not_ replicate the standard Macintosh keyboard layout. Instead it adds the set of dead-keys and extended characters from the Apple layout to a normal Windows UK keyboard layout, so so `"` will still be found on the `2` key (not above `'`), `~` stays at the right of the keyboard, not the bottom-left, and backtick is at top-left.

You will need the Microsoft Keyboard Layout Creator (MKLC) tool to turn this file into an installable key layout (As of June 2020, the MKLC tool is here: https://www.microsoft.com/en-us/download/details.aspx?id=102134 )

### To use

1. Open the .klc file with the MKLC program 
2. From MKLC, choose Project › Build DLL And Setup Package.
3. You’ll see a list of warnings about the keyboard not being compatible with Code Page 1252 - that’s okay; that’s because it adds the ability to type Unicode characters.
4. The tool will create an installer file.  Click `setup.exe`
5. Once installed, you can choose "English United Kingdom (Extended)" from the keyboard input menu (bottom right of taskbar, where it says "ENG")
