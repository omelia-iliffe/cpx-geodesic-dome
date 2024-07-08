# INTERACTIVE CIRCUIT PLAYGROUND GEODESIC DOME
**Two of our FABourite things; combined!**  
**A Project by Wendy and Omelia**  

## Resouces
* The circuit playground holder is a remix of [**Circuit Playground Express Snap Fit Mount with Alligator Clip Cutouts** by **paulblankenbaker** on thingiverse](https://www.thingiverse.com/thing:3982715)
    * which itself is a remix of [Adafruits **Circuit Playground Express Snap Fit Mount**](https://www.thingiverse.com/thing:3878226)
* The fantasic **Joinery: Joints for Laser Cut Assemblies** project for the joins between each triangle in the dome.
* [**Domerama 2v geodesic dome calculater**](http://www.domerama.com/calculators/2v-geodesic-dome-calculator/)
* Inkscape for drawing and modifying the triangles.

## Components
### Geodesic Dome
To create the geodesic dome I created triangles in Inkscape. The triangles need to be the exact dimensions in order to create the dome. The Domarama website was helpful to do the inital calculations. We are using a **2V** dome design.  
We used a brother ScanNCut to cut out the triangles. There are some solid ones and some with different pattern cutouts. Its fun to have a mixture.
You need 30x AAB, and 10x BBB triangles

### Circuit Playground Base
The circuit playground base is created with two 3d printed parts, some mesh fabric (we used tulle), copper tape, and conductive thread.
#### Bottom Plate (with fabric)
Wendy designed this in TinkerCAD, importing vectors she'd made in Inkscape as an SVG. The vectors were based on the measurements from the triangles. She extruded the spaces between the vectors and added some dome shapes from TinkerCAD to act as feet and printed upside down to avoid using support.  
It has a pause added a few layers after starting so the fabric can be added. Lay the fabric over the print, tape the sides to the bed, and resume the print. 

![](/images/base_tulle.jpg)

#### Top Plate (with circuit playground)
This was created in TinkerCAD again, using vectors to create some shapes to the Circuit Playground Express Snap Fit Mount with Alligator Clip Cutouts model.  
This creates a secure hold for the Playground and a place for the geodesic dome to slot in.

## Assembly
### Dome
After cutting out 30xAAB triangles and 10xBBB triangles, carefully fold each of the tabs, make sure each triangle is folded the same way. 
Then assemble them together following these images as a guide
![](/images/2v_assembly_large.jpg)

This is what the different shapes look like - AABs, BBBs, and AABs with holes in the centre.
![](/images/dome_components.jpg)

This is one 'group' of the ABB triangles look like joined together, with the long sides on the outside.
![](/images/dome_single.jpg)

Two 'groups' of ABB triangles joined together using the AAAs.
![](/images/dome_elements.jpg)

And then, a view of the inside and the outside of the full dome... tahdahhhh!!!
![](/images/dome_inner.jpg)
![](/images/dome_outer.jpg)

### Circuit Playground Base
* Slot the 2 locating tubes into the circuit playground holder and slot that onto the base plate with the fabric.  
* Cut 6 pieces of conductive thread and tie them around pins A1, A2, A3, A4, A5, and A6. 
* Cut 6 pieces of copper tape and adhere them to the outside of the top plate **pinning a strand of conductive thread underneath it**. These will be our capacitive buttons for interaction.

### Upload the code
Find the .uf2 file in the files folder and upload this to the circuit playground. There are six musical notes with a light effect associated with each of them, so you can play a tune and make a light show at the same time.

### Finally,
Place the geodesic dome on top. Enjoy the lights and sounds as you touch the copper tape.
