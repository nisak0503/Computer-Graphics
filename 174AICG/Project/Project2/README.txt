Summary:
  This is an animation on Pokemon world, which will be introduced before every Pokemon movie. 
  "Dazzling and inspiring, the amazing creatures that thrive on this planet. Get the Pokemon world its mystery and wonder. Arriving an abundant numbers that are hard to imagine in the sky, in the sea, on mountains and everywhere! Some of them united as friends, others live alone. Pokemon together with human contribute to the diversity of this planet."

  So is earth. 


Implementation:
  I imported some .obj files from https://www.models-resource.com and some .png images from Internet.


custom shape:
    dependencies.js
    line 26 - line 97
    class mountain extends Shape
    It is a volcano built with sub_triangles, textured with mountain image.

usage of look_at()
    1. camera moves from space to earth
    2. change to volcano scene.
    3. also follow Flying Togetic.

Hierarchical Object:
  The seesaw is made up with 
    1. rotating diglett-shaped base, which is drawn by ellipses.
    2. a closed cone as diglett's hat, which can swing.
    3. a yellow long cube, attached with two red seats. It moves due to the weight of two buddies, Pichu and Marill.


by kasin
2017 Fall