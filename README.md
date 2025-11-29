
# Umamusume Shaders for Blender (WIP)
A Blender shader for Umamusume: Pretty Derby. Still under development, but I thought it might be better to get it out there now and improve it later.
![Screenshot of a model with the shader applied](https://i.ibb.co/gM9gJqy5/Screenshot-2025-07-18-004120.png)
## How to apply
1. Open a blend file with a model you have extracted, and then **append** the "Icosphere of materials" Collection. It should contain an Icosphere containing the materials and the "sun" object (**DO NOT DELETE**)
![Screenshot of the collection to append](https://i.ibb.co/TBSSFxhD/Screenshot-2025-07-18-010103.png)
2. Apply the material to the model. There are 4 main texture groups using the same shader:
	**A. Body
	B. Hair
	C. Face
	D. Tail**
	Meaning **you would have to make 4 copies for each parts**.
	![Screenshot of expected material list](https://i.ibb.co/Y44gch5Z/Screenshot-2025-07-18-010548.png)
3. In the shader editor, **apply the appropriate textures to the appropriate slots** (i.e. Base texture goes to base, etc)
![Screenshot of texture setup](https://i.ibb.co/SDpqJkpV/Screenshot-2025-07-18-010729.png) 
4. For the **outlines**, I have provided a simple outline material and geometry node setup for now. Simply **duplicate the mesh, and give it a geometry node modifier, and set it to the one provided**.
![Screenshot of Outline setup](https://i.ibb.co/j9mvm4D1/Screenshot-2025-07-18-011324.png)

### If you have any questions, or are understandibly confused, feel free to post an issue, and/or contact me via Discord.
[@looperhonstropy](https://discordapp.com/users/294392873074425856) on Discord
[@honstropy](https://twitter.com/honstropy) on Twitter

# Special Thanks
@AerthasVeras for sharing the dot product node setup
@elagrimm and @mojuko for helping with the face shading setup (even though it will be short-lived)

# To-Do List
- Rework Face shading with better method
- Better Documentation
- Promotional Materials
