# Building tracks

1. CLick the "New track" button.
This will spawn a new Tycoon collection piece in the world. All your track pieces will be parented under this actor.

![](/img/new_track_button.jpg)

2. Select the mesh you want to deform. (See [Preparing custom meshes](prep_mesh.md) for a step by step guide.)
> Tycoon will display a warning for high poly meshes with more than 20k vertices.  
To adjust this amount click on the collection / main actor and search for warning in the details panel.

3. Adjust the sliders. 
> Direction has no effect when the Bend value is 0.0.  
You can use the preset buttons to quickly go to 90 degrees.

4. To add a new piece to the track press the "Add" button, the "|" / straight button adds a straight piece without bend / direction or twist values.

# Convert meshes to spline (Experimental)

1. Click the "Convert spline" button.

2. Click 'Yes'

![](/img/converttosplinedialog.PNG)

>Your mesh might deform incorrectly if your mesh is longer than 150 cm. Tycoon can auto slice / correct this using the slice feature.
This will create a duplicate shorter version of your mesh.
Mesh slice quality: Quality slider for the final spline. (Higher is more points).

3. Move / adjust the spline points of the Tycoon spline component part of your Tycoon main actor.

![](/img/trackaddui.PNG)




