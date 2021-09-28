# Ursina-Modified-Mesh-class


A modified mesh class that allows you to send pre calculated tangents and bitangents to the shader that you are using.

For vertex attributes in the shader:

position---->vertex,
uv---->texcoord,
normal---->normal,
bitangent---->bitangent, 
tangent---->tangent,


Just replace the mesh class in your copy of ursina with the mesh class provided over here and set the parameter TB to True while creating the mesh
vertex,uv  and triangle lists should be lists of lists [ ((0,0,0),(0,0,0)) form not (Vec3(0,0,0),Vec3(0,0,0)) ]
