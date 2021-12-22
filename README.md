# Ursina-Modified-Mesh-class


A modified mesh class that allows you to send pre calculated tangents and bitangents to the shader that you are using.

For vertex attributes in the shader:

position---->vertex,
uv---->texcoord,
normal---->normal,
bitangent---->bitangent, 
tangent---->tangent,


Just replace the mesh class in your copy of ursina with the mesh class provided over here and set the parameter TB to True while creating the mesh
vertex and uv data should be in the form of Vec3 and Vec2 while the triangle data should be in a list.
