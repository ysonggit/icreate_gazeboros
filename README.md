icreate_gazeboros
=================
In each sdf file, there is a uri tag:
 &lt;uri&gt;model://create/meshes/create_body.dae&lt;/uri&gt;

If necessary, change it using local or absolute path:
For example, I copied all files in this repo to the folder in $/home/yang/code/catkin_workspace/src/create/, 
then I change it to be 
&lt;uri&gt;/home/yang/code/catkin_workspace/src/create/meshes/create_body.dae&lt;/uri&gt;
