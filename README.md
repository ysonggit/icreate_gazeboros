icreate_gazeboros
=================
In each sdf file, there is a <uri> tag:
 <uri>model://create/meshes/create_body.dae</uri>

If necessary, change it using local or absolute path:
For example, I copied all files in this repo to the folder in $/home/yang/code/catkin_workspace/src/create/, 
then I change it to be 
<uri>/home/yang/code/catkin_workspace/src/create/meshes/create_body.dae</uri>
