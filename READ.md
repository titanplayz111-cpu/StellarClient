abric and Quilt profiles only generate a version .json file and inherit the base Minecraft game .jar.
Patched isProfileInstalled in 
minecraft.js
 to recognize Fabric/Quilt profiles without looking for a non-existent loader-specific .jar file. This successfully stops the launcher from prompting you to "INSTALL" modpacks that are already fully configured.
