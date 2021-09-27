# Unity-Color-Cycle-shader-with-Mask
I used this shader as a base and added a mask on it: https://github.com/UnityCommunity/UnityLibrary/blob/master/Assets/Shaders/2D/Effects/ColorCycle.shader 
I changed this shader so I can have a mask on it as well, which prevents the masked parts to be cycled. So only the parts which needs to be moved are moving.
If you don't need the mask you can just get the one which is linked above. They both doing the exact same thing, just this one has 1 additional operation
where I add the masked texture on top of it.
