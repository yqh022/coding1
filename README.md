
# coding1
# Final Project
# MIMIC Link:https://mimicproject.com/code/3dcba26e-faa2-fc78-67ce-26861bb147ed
# Video:https://youtu.be/IiJmQhn07xw
# Project Description
For the final project of Coding One course, I designed a scene by combining three.js and constructed music snippets.
## Audio:


I first set up a "play" button to control the start of the music, use samples and clocks to load the selected music, and use regulating frequency and interpolation to build new combined music pieces that run in the background of the scene.I used BPM  for setting the rate of playback by how many events I want to trigger each minute.
## Three js:
I used the sky box to create a 3d world, selected the pictures and moved the box to create the stars.

I want to imitate the shuttle movement of small meteorites of different shapes, so by constructing an OctahedronGeometry, IcosahedronGeometry and a SphereGeometry, they arc in different speeds and angles.I had seen a lot of examples on the threejs web page where I found it interesting to build transparent objects, and then I used it to set up seven SphereGeometry orbits for the main body's transparent shell.They are like snail shells, and the spheres are stacked at different angles.Small meteorites can pass through transparent spheres as they move.

I built three different light sources and used TorusKnotGeometry to build a ring like object with a transition between light and shade on the front and back.The main item was very light in color, so I built stacked glowing cubes and placed them on TorusKnotGeometry, making the small cubes appear in different random colors. cube. * position.set(rand(40, 70), rand(-20, 20), rand(-20, 20));*  Change the number of squares by changing its position setting.

## Final Display:
The following picture is the final display of my project.
<img width="1189" alt="截屏2022-12-05 下午4 06 15" src="https://user-images.githubusercontent.com/119873931/205689935-51ff0951-9b5c-422b-9e76-6a26227ef5d4.png">
## Sounds:
I added audio using the Maximilian library.I found some spatial electronic sounds, and I think they fit my scene.
