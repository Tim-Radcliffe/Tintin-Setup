These scripts are loaded automatically when the 'eq' command is used.

The filename needs to match the text that appears in the eq command for that piece of equipment.
Where a wildcard is needed in the filename, use "x25x2A", which is the hex conversion of "%*".

Every one of these scripts will be automatically unloaded when the 'eq' command is used, then reloaded if a match found. This means you will only have the scripts loaded for the equipment currently being used.