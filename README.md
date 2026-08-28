# GeoAnim
Minecraft mod that adds support for .geo.json and .animation.json files for resource packs!

# How does it work?
First, you must make a resource pack like usual, then in assets/minecraft/ create a folder called "GeoAnim", inside another folder called "entities" and last but not least, a folder with the name of your entity (zombie, creeper, etc).
Next, using Blockbench with the CEM plugin + Geckolib plugin convert your CEM to a Geckolib project and then you can create a .geo.json which is the model of the entity or a .animation.json, which is the animation of the mob (Please note that some model details such as UV, texture, pivot points or etc can be different since you're using bedrock models!). To make the game automatically read the animations you must name them "animation.nameofyourentity.idle/walk/etc"
Once you're done, put your files inside the folder and done! If you want to make a step further and add more animations with specific conditions (For example baby-only animations, hurt animations, swell animations, etc) you can use the GeoAnimEditor.

# How do you use the GeoAnimEditor?
It's pretty simple, all you gotta do is create a .gaca file inside your folder like "zombie.gaca" and open the .exe, once you're in open the .gaca and then the .animation.json (or optionally the .geo.json too) and then you'll see all the animations on the right side. Click the button next to each box and you have three options, you'll see "Conditions", click that and the editor opens.
You can either use the blocks like scratch or use the java editor by scripting manually. Once you're done save the .gaca using the button at the top and you're done!
