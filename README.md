# Muruchi
This is my first monster model sculpted in Blender. Muruchi (ムルチ) is a fish-like monster in Ultraman TV series.

![AI_2024-04-22-19-53-46-166](https://github.com/user-attachments/assets/e5d31b10-012c-413c-a1a4-22c3033b1cff)

## How to Use

Download the **.zipmod** file for the latest version on the [Release](https://github.com/Blatke/Muruchi/releases) page, and put it into you **mods** folder

The mod was made as a Studio item. Enable its **FK** function on the anim tab to rotate its joints of bones. If you have **MoveController**, which is the plugin in Studio helping with FK nodes selecting and rotating, that could be more convenient. 

![AI_2024-04-22-19-56-13-425](https://github.com/user-attachments/assets/74e7de3e-bb51-4b5a-b92e-c4f1beb1759f)

This item was set to Map Layer, which means it will not be affected by chara lights. If you need to, you can use **Item Layer Edit** the plugin to shift its layer. 
(Most of the plugins can be found on -- for HS2: https://github.com/ManlyMarco/HS2-HF_Patch/blob/master/Plugin%20Readme.md ; for AIS: https://github.com/ManlyMarco/AI-HF_Patch/blob/master/Plugin%20Readme.md)

![AI_2024-04-22-19-56-35-892](https://github.com/user-attachments/assets/3701ab3c-718c-44ca-a7c6-558cbb428740)

Also, the source file in format of **.blend** was put in the shared folder. Just feel free to use it.

I tried my best to rig the meshes and bake the textures. It still has something imperfect, such as the tail cannot be smoothly morphed when twisting it because each vertex is affected by only 4 bones at maximum in Unity 2018, which is the game engine of HS2. 

I'll appreciate if there is any referrence to me that gives me a credit when you use my mod or source file.

In addition, this mod of Muruchi has no tongue in his mouth, and I don't plan to individually create a tongue for him or any other monsters. You can use my mod of [Sharp Tongue](https://github.com/Blatke/Sharp-Tongue-HS2-AIS-mod) and attach it (by using **NodeConstraints** the plugin, for example) to his mouth. The advantage is that you can rescale the tongue, as your wish, without changing Muruchi.

## Renders
![AI_2024-04-22-19-52-54-621](https://github.com/user-attachments/assets/533dbee3-cb23-43de-86e8-f4c6917e34f9)

![AI_2024-04-22-19-53-06-794](https://github.com/user-attachments/assets/41773845-1eb7-471e-af7f-48749ca09fb5)

![AI_2024-04-21-21-03-22-571](https://github.com/user-attachments/assets/7821a4ce-70ec-4e14-93ee-5238c07b9514)
