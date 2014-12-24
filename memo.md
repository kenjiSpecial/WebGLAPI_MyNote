1129:

Note that the value that is assigned to gl_Position has 1.0 added as a fourth component. This four-component coordinate is called a homogene

The homogeneous coordinates use the following coordinate notation : (x, y, z, w). The homogeneous coordinate (x, y, z, w) is equivalent to t

<br>

1831 - :

###Drawing Multiple Points

WebGL provides a  convenient way to pass multiple vertices and uses something called a buffer object to do so.

A buffer object is a memory area that can store multiple vertices in the WebGL system.


Thre are five steps needed to pass multiple data values to a vertex shader through a buffer object.

1. Create a buffer object(gl.createBUffer())
2. Bind the buffer object to a target(gl.bindbuffer())
3. Write data into the buffer object(gl.bufferData()).
4. Assign the buffer object to an attribute variable(gl.vertexAttribPointer()).
5. Enable assignment(gl.enableVertexAttribArray())

