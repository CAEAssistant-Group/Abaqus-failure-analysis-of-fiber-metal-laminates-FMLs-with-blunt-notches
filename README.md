# Abaqus-failure-analysis-of-fiber-metal-laminates-FMLs-with-blunt-notches
In this project, the Hashin damage model is implemented in Abaqus to conduct the failure analysis of fiber metal laminates (FMLs) containing a blunt notch.
Fiber metal laminates (FMLs) consist of thin aluminum layers bonded with intermediate glass fiber-reinforced epoxy layers. These materials are highly regarded in the aerospace industry for their exceptional properties, including high fracture toughness and low density, especially when compared to solid aluminum sheets.

![image](https://github.com/user-attachments/assets/89c12277-6dda-4a10-9bff-12e089fe3189)

The laminate presented in this project consists of three aluminum layers and two layers of 0°/90° glass fiber-reinforced epoxy. It is subjected to uniaxial tension along the longitudinal direction. The Hashin damage model is used to analyze the problem.

To solve the problem, the static solver of Abaqus is used. As it checks for convergence control in each increment, the obtained results are more reliable compared to Abaqus explicit solver. However, convergence issues may still occur due to the nonlinearity of the problem and using the Hashin damage model when using this solver.

Notice that, here, an Abaqus input file along with its ODB is attached. In this model, behavior of a laminate sample is analyzed using the Hashin damage model in Abaqus. However, if you would like to receive training on the Hashin damage model in Abaqus and master its application, you can visit our website, where we offer workshops and lessons on using the Hashin model for analyzing the behavior of various materials, ranging from fiber composites to wood, in Abaqus.

![image](https://github.com/user-attachments/assets/73f9ecd9-bb1c-4dce-bf2a-04693d33eca4)

Please note that the INP files included in this repository are sourced from the Abaqus documentation for versions 2022 and 2024. To obtain INP files for other Abaqus versions, please consult the official Abaqus documentation.





