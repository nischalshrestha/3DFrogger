# 3DFrogger

### Requirements:

The entire project can be found here: https://github.com/nischalshrestha/3DFrogger

If you want to run it locally on a machine clone it with git.

The main requirement is threejs and a way to run a local server if running on a
local machine since Chrome will complain about file access permission for texture
and obj loading. The project is tested with the program http-server.

If you run the program with the link below, you don't need to run a local server.

You can play with it here: https://nischalshrestha.github.io/3DFrogger/

### Description:

This is a 3D version of the classic arcade game, Frogger. I've made the game
appear more 3D by adding in Phong shading, soft shadows, perspective camera,
ambient, and point lighting with the help of threejs library.

The rules are similar to the classic game, where the objective is to not get hit
by a vehicle or land on the water and grass on the other side. The frogger also
cannot stay on the log or turtle for too long because it can die if it hits the edge.
The main goal is to get to the other side and land on one of the swamps.

The frog is safe on the turtle shells and the logs and have to use them to get to
the swamps. When landing on the swamp, a placeholder frog is put there to give
the player the visual feedback (in addition to the audio feedback) that they have
already visited that particular swamp.

### Screencast

The walkthrough / demo can be found here: https://youtu.be/bXakJw_jpH4
