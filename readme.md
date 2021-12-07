# Bottom Up Problem Solving Dataset
## Usage
Use [obsidian](https://obsidian.md) to open this entire project folder as a vault. Sample data is loaded in from the `sample data` folder and the graph filters are already preconfigured. Simply create new files to start your own analysis.

## Sample data
You can get rid of the sample data by simply deleting the folder `sample data` or by adding the following filter to the graph menu:

```
-path:"sample data"
```

## Templater Plugin
The templater plugin is used to automate the structure of new notes, which are used for the seperate tags `#data`, `#opportunity`, and `#solution` and found in the `templates` folder. After creating a new note and naming it, the following hotkeys can be used to populate the file with a title and appropriate tags:

- `opt/alt + shift + d` - data note
- `opt/alt + shift + o` - opportunity note
- `opt/alt + shift + r` - solution note

Please note, safe mode needed to be deactivated to use templater. You may get a warning stating that safe mode is turned off and this is why. You are free to keep safe mode on and manually fill out each note with the corresponding tag if you prefer.