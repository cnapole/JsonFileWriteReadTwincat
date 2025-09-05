# JSON file creation and variable read from JSON in Twincat 3

Goal: how to create a JSON file and read the objects afterwards

Functions FB_ReadJsonReal and FB_SaveFile are the one that are meant to be use in other projects. FB_ReadJsonReal was made to read LREALs but it can be extrapolated to other formats. FB_SaveFile is a conventional save file routine in twincat.


## Requierements
- Twincat 3 (4024 but 4026 can be ok to be use)

## Further tasks
- Include more reading formats like boolean, etc.