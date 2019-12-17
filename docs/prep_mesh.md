# How to use custom meshes

1. Create your mesh in your DDC application of choice.

2. Make sure the pivot point is on the starting edge of the object.

![](/img/TycoonPieceMesh.PNG)

3. Import your mesh into Unreal Engine.

4. Select the mesh in the Mesh input dropdown.  
This mesh will be used on the next piece, press "Apply to all" to replace existing meshes with this select mesh.

![](/img/custommeshdropdown.png)

5. Press the "Add" button.

![](/img/CustomMeshExample.png)




# Current limitations 

1. Object must be facing the Y axis. (Tycoon will currently only build in the world Y axis.)

2. Only one material index is supported for track pieces.

