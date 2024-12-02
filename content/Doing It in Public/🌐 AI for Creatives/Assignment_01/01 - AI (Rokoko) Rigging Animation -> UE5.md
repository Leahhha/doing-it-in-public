## What is Rokoko?
- Rokoko is a motion capture (mocap) system that includes AI tools for capturing and animating motions.

	A free AI tool that allows users to: 
	- Upload a video of a person moving 
	- Record themselves with a webcam or phone 
	- Automatically extract the motion file
💡 It is a great tool for capturing and animating motions for my NPC character in UE5

## Experiments Process:
1. Select a short video (under 15 seconds).
2. Use Rokoko to auto-rig the animation.
3. Export the rigged animation.
4. Import and adjust the bone positions as needed.
5. Add the animation to the scene –> Done!!!


## Attempts:

1. Upload a figure skater's video (3D real-life photo)
   
   I notice it is losing the motion details.

   ### Rokoko - AI Auto Rig
   ![[skater01.mov]]

   ### UE5 - Add the NPC Animation to the Scene
   ![[rokokoUE5.mov]]
   
2. Upload an animation (2D Character)

   - **2D animation character** - Mickey Mouse  
   I chose this character because it has abstract motions.
   
   - As expected, Rokoko cannot recognize the motion correctly, not even 20%.


## Next steps: 
1. Find engaging short videos to incorporate into the NPC character interactions.
2. Develop a method to attach animations to custominzed character model.


## Conclusion: 
### ⚠️ Tips for using Rokoko
1. Keeping animations simple and similar to NPC movements will yield the best results.
2. It only matches the UE5 Mannequin Skeleton 


## Credits: 
This is the tutorial video, [Rokoko Unreal 5 - Video Motion Capture (2 Minutes!!)](https://youtu.be/IhrYBl0ZygY?feature=shared), I followed to get the animation from a small TikTok video to UE5.

