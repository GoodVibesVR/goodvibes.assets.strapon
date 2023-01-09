# GoodVibes.Assets.Strapon
Strapon prefab rigged and prepped for VRChat to work out of the box with GoodVibes.

## Contents
This package contains everything you need to quickly put this strapon on your avatar. The strapon has a vibrator function that vibrates in 3 different strengths, which will also vibrate your Lovense toys accordingly and you will also get feedback towards the base of the penetrator.

### This package contains:
- A rigged strapon model
- Materials
- Textures
- Normals
- Emissionsmaps
- Unity package 

## Relies on
- VRCSDK 3.0
- Poiyomi Pro 8.1+ shader

## How it works
The strapon prefab is rigged with TPS, Contact Senders and Receivers in order to be able to satisfy yourself and your partner(Glory to the pegging!). It's setup be relatively realistic, in the way that you won't be able to feel with the strapon but you'd be able to feel something at the point where you'd get resistance, in this case the base of the strapon. The strapon has a vibrator with a button that can be pressed by both you and your partner, and will vibrate in 3 different strengths and your Lovense toy accordingly. It's rigged in a way that if you animate the pickup of the strapon you'd stop feeling the vibrations as well.

Setting up the strapon on your model will expose the following parameters for the GoodVibes client:
Parameter			| DataType			| Description			
------------------------|---------------|--------------
GoodVibes/Orifice	| Float	| Vibration feedback 
GoodVibes/Penetrator	| Float	| Resistance feedback 

## Help and support
Are you having issues?  
Want to support or contribute the project?  
Want to hang out?  

Please head over to our [Discord](https://discord.gg/R2tTCB7MNC).

[A video tutorial can be found here](https://youtu.be/k4TKMQDYva4)

## How to set it up
The README.txt contains all information on how to setup the prefabs in this package if you happen to lose this repository.
### 
### Setup the strapon:
1. Navigate to /GoodVibes/Strapon/Prefabs in your project files
2. Drag the following prefab into your scene:
	- GoodVibes_Strapon
3. Place and resize the strapon as you see fit on your model
4. When you're happy with the size and placement move the strapon into the _Hips_ bone in your _Armature_
5. Unpack the prefab completely
6. Move the object _"GoodVibes_Strapon_Receiver - Move me to hip"_ to your _Hips_ bone
7. Feel free to remove the _"Move me to hip"_ part from the name
8. Download and install _VRLabs Avatars 3.0 Manager_ from https://github.com/VRLabs/Avatars-3.0-Manager
9. Navigate to _/GoodVibes/Strapon/Controllers_ in your project files
10. Merge the _GoodVibes_StraponController_ controller with your avatars FX controller using VRLabs Avatars 3.0 Manager tool
11. Navigate to /GoodVibes/Strapon/Expressionparameters in your project files
12. Add the _GoodVibes/Strapon/VibrationStrength_ _int_ parameter to your own ExpressionParameters
***TIP:** Don't forget to add the prefab to the Ignore Transform list of any VRC Phys Bone component affecting the parent*

## Credits
- Hoshou Neko (https://hoshou-neko.sellfy.store) for gifting the strapon model for this free prefab.
- Lat3xKitty (https://twitter.com/Lat3xKitty) for testing these instructions
