# InfoStructureVR
A software project, which six students, including me, made within a year. It is about loading in BIM data from buildings and to visualize them, so one can explore it in Virtual Reality. This repository includes an example of a building, which was imported through data smith inside UE4. The meta data provided inside the application is extracted from the BIM data and converted to a .csv-file. This csv-file is imported to UE4 and the data is asigned to the right object at runtime.
For a quick overview watch this video: [Kurzfassung Projektvorstellung](https://www.youtube.com/watch?v=K2HljHToOYE)

Check the responsibilities in the documentation.

### MedadatenAusExcel

A Java application to convert an excel file, which was exported from Simple BIM, to csv-format.

### Infostructure VR_Temp

Empty template which uses meta data from the Datasmith import, but it is not much data. To change the meta data to the data from the generated csv-file:

Inside UE4 Project go to Content/CollaborativeViewer/UMG/GameMenu/NewContextualWidget/NewContextualWidgetBlueprint
connect the exec path from "ReadyToSpawnMeta" to the unlinked part above.

### Infostructure VR_ImportedProject

Template project with imported building and meta data from csv-file.

### Infostructure VR_Dplmt

The final build application with imported building and meta data from csv-file.

### Infostructure VR_O_Quest

Propagated the windows project to an android project, but not as a ASTC! (Did not work on our local PC)
