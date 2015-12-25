#Ogre Basic Tut corrected for working with codeblocks


plugins in /usr/lib64/OGRE

.cfg files need exact path for essential zips(my guess)
Global Compiler Settings:


Add the following in linker 
OgreOverlay
OgreMain
(follow order)

add search dirs in following order

/usr/include/OIS
/usr/include/OGRE/Overlay