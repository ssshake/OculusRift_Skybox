This is a unity package built using a script authored by the user Nora on oculuvr developer forum. I creatd this to make it easier for new people to use Nora's script. 

Here is a copy/paste of instructions:

-----------------------------------------------
Re: How to apply the Rift specific skybox?

Postby brendenfrank » Sun Aug 04, 2013 9:43 pm
I have the script working, instructions are as follows:

1) Make an empty game object
2) Attach the script
3) Drag your (previously unity skybox) material onto the "Skybox" slot
4) Run the game
5) In the scene hierarchy tab, expand the empty game object to find that several planes were created and mapped to your skybox texture. These planes form a physical box around the player if your Radius is set correctly,

Note: if using a box, turn the segments down to 1 or else you are just wasting polygons.
----------------------------------------------

Keep in mind that for the unity package I've created, the empty game object already exists, and the script is already attached. So you shouldn't have to perform the steps listed above. I've just included them in case you run into trouble.
