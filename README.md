# GAME_PROGRAM-EX--8
## Landscape Creation and Foliage in Unreal Engine
## Aim:
  To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for realistic environment generation.

## Procedure:
   ### Create a New Landscape:
   • Open your Unreal Engine project.
   • Go to the Modes Panel and select Landscape.
   • Set the desired section size, number of components, and overall resolution.
   • Click Create to generate the landscape.
### Apply a Landscape Material:
   • In the Content Browser, create a new Material and name it M_Landscape.
   • Open the material and:
          ▪ Use Landscape Layer Blend to blend textures (e.g., grass, rock, dirt).
          ▪ Connect appropriate texture samplers to different layers.
          ▪ Output the final blend to the Base Color, Normal, and optionally Roughness inputs.
   • Save the material.
   • Select the landscape in the scene, go to the Details Panel, and assign M_Landscape to the Landscape Material slot.
### Add Foliage:
   • Go to the Foliage Mode from the Select Mode dropdown.
   • In the Foliage Panel, click the + icon to add Static Meshes (e.g., trees, grass, bushes).
   • Adjust settings like Density, Scale, and Randomness.
   • Use the brush tool to paint foliage onto the landscape.
### Output:

<img width="1540" height="828" alt="image" src="https://github.com/user-attachments/assets/c1ef3d88-7da0-42e0-a880-74e3081a5a7c" />

<img width="1519" height="838" alt="image" src="https://github.com/user-attachments/assets/cf6e8cef-efa7-43a4-91d1-70b91f2fd7e5" />

### Result:
  A landscape and Foliage in Unreal Engine was successfully created.
