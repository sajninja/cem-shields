Square Shields. By SajNinja.

This pack changes the shield model using Optifine CEM.
I pulled this model from my project "Saj's Mod", where these shields are their own items with new functionality.
Getting these new shields to display banner patterns was a similar process to using Optifine.

The shield model was built using the CEM Template Loader on Blockbench.
This tool provided the required groups to make this project work

It is unclear as to whether shield models can be changed through vanilla custom item models alone, since the shield uses an entity model.

In shield.jem, there is no field for "texture".
If the texture was specified, then the model would not be able to display a banner.
Leaving it blank allows the game to act as it normally would, and we can replace the vanilla textures with our own.

In textures/entity/shield, all the banner patterns have been adjusted to become square and fit the new shield.
Their position on the texture aligns with that of the shield's plate, ensuring they display in the correct place.

The shield item models serve to make the shield look good when displayed, making it bigger and positioned correctly in the player's hand and in GUIs.