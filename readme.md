# AR Poster Code

This branch contains all of the code required for the AR augmentation of your poster for project two. 

**Code currently supports:**

- Static Images
- Sound

**Code currently works on:**

- Android
- iOS
- Web Browser



###To Generate the AR Marker

Go to: <https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html>

1) Find an image to upload, should be a square image. If it isn't, it will be scaled into a square shape and distorted.

2) Click upload, select image.

3)Click download, download .patt file. Put the .patt file in the data folder, change the corresponding code so that the camera knows to look for your .patt file.

4) click on "PDF ONE PER PAGE" (or any of the other options) to download a PDF to print as a marker. Make sure you have any ad blockers disabled or nothing will happen. If this fails, you can always take a screen shot and crop out the marker to make your own.

**Note:** markers are sometimes recognized as other markers if they are not distinct enough. You'll have test out different images to make sure they work correctly. Markers must include a white border around the black square in order to be read correctly.



***Code created by Lucas DiMonte.*** 