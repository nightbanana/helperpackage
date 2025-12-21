This is a source code note for the helperpackage project. 

Since the project is in its early stages and I'm adding things gradually, I've decided to keep it **closed-source** for now, and perhaps in the future (if the project moves forward) open it completely to open-source. 

Here are some areas where the project has and will have closed-source code: 

- Main script code: it's not an explicit script, but rather a compiled binary.
- Auxiliary scripts for extra functions: scripts added as extra functions that wouldn't fit in the main binary will also be compiled binaries (shell).

However, only the core (main binary and auxiliary shell scripts of the main binary) will be closed source. 

- Scripts that **perform functions called by the main binary**: scripts that perform their own functions, and not functions of the main binary that are in other scripts, will be open source without compilation.
A clearer explanation would be:

The current binary performs all the functions that exist so far (in v1.1 of the helperpackage). It calls the guides, checks for updates, and other stuff.

If a situation arises where a function **from the binary** needs to be written and saved in a separate shell script, it will be saved and **compiled** just like the main binary. 

But if it's a script that **is not a binary function** (for example: a special function that requires Python and isn't called via flags), it will be a pure script (file.extension, such as script.py). 

For now, the project structure will remain as is, and in the future there will be more planning to determine whether or not to  make it fully open-source.
