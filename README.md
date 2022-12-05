# coding1
# Final Project
# MIMIC Link:https://mimicproject.com/code/3dcba26e-faa2-fc78-67ce-26861bb147ed
# Video:
# Project Description
For the final project of Coding One course, I designed a scene by combining three.js and constructed music snippets.
## Audio:
I used the sky box to create a 3d world, selected the pictures and moved the box to create the stars.

I first set up a "play" button to control the start of the music, use samples and clocks to load the selected music, and use regulating frequency and interpolation to build new combined music pieces that run in the background of the scene.
## Three js:
I want to imitate the shuttle movement of small meteorites of different shapes, so by constructing an OctahedronGeometry, IcosahedronGeometry and a SphereGeometry, they arc in different speeds and angles.I had seen a lot of examples on the threejs web page where I found it interesting to build transparent objects, and then I used it to set up seven SphereGeometry orbits for the main body's transparent shell.They are like snail shells, and the spheres are stacked at different angles.

I built three different light sources and used TorusKnotGeometry to build a ring like object with a transition between light and shade on the front and back.The main item was very light in color, so I built stacked glowing cubes and placed them on TorusKnotGeometry, making the small cubes appear in different random colors.
## Final Display:
The following picture is the final display of my project.
## Sounds:
I added audio using the Maximilian library.I found some spatial electronic sounds, and I think they fit my scene.
