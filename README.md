# Unreal2DHeatmap
2D Heatmaps for Unreal Engine
![image](https://github.com/CasTrines/Unreal2DHeatmap/assets/90839770/92c4d4d9-a5bb-4a30-97a3-2161a5c1b889)

A very simple drag and drop Heatmap for anything 2D in Unreal engine.
This heatmap plugin allows you to export the heatmaps as images, import them easily back into the game and gives the choice between a Top-Down view and a Side view.

Additionally, as many actors as needed can be added for the heatmap to trace, by default it takes the player character to trace.
There is no limit to how many heatmaps can be placed, however performance impact of doing such has not been tested.
For public builds, you likely want to hide the heatmaps ingame so that they are not visible in the background, in-engine this can be set back to visible to view heatmaps during play, everything can be done during playtime.

# Imports and Exports
You can find the Exports inside of the Exports folder in the Plugin/Content folder.
To import images, make sure the Heatmaps you want to import are placed inside of the Imports folder, located in Plugins/Content.
For the importing to work, the name of the image needs to be the same as the Heatmap placed inside your level, so it will be applied to the correct one.

# Setup required to open Widget
![image](https://github.com/CasTrines/Unreal2DHeatmap/assets/90839770/28e89f48-61a7-4109-96cf-1506cf5a942a)
![image](https://github.com/CasTrines/Unreal2DHeatmap/assets/90839770/6f80119a-4fb3-4f57-a8b4-abe42036e66c)

# Credits
This heatmaps is based on a tutorial from Robert Potter and expanded upon to be more useful in a real production setting, such as the addition of importing, exporting, additional perspective to trace and being able to trace whatever actor you want.
Link to original tutorial: https://www.youtube.com/watch?v=QL51f8qdsm8
