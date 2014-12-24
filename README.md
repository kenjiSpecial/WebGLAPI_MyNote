GLAPI
===============
<br>
```
gl.clearColor(red, green, blue, alpha)
```

Specify the clear color for the drawing area.


<br>

```
gl.clear(buffer)
```

Clear the specified buffer to preset values.In the case of a color buffer, the value specified by **gl.clearColor()** is used.

example:
**gl.clear(gl.COLOR_BUFFER_BIT);**

<br>


```
gl.drawArrays(mode, first, count)
```

Excecute a vertex shader to draw shapes specified by the mode parameter.

mode: Specifies the type of the shader to be drawn.gl.POINTS, gl.LINES, gl.LINE, gl.LINE_LOOP, gl.TRIANGLES, gl.TRIANGLE_STRIP, and TRIANGLE_FAN.

first: specifies which vertex to start drawing from(integer)

count: Specifies the number fo vertices to be used(integer)

```
gl.getAttribLocation(program, name)
```

Retrieve the storage location of the attribute variable specified by the name parameter.

program: Specifies the program object that holds a vertex shader and a fragment shader.
name   : Specifies the name of the attribute variable whose location is to be retrieved.


```
gl.vertexAttrib1f(location, 1f);
gl.vertexAttrib2f(location, 1f, 2f);
gl.vertexAttrib3f(location, 1f, 2f, 3f);
gl.vertexAttrib4f(location, 1f, 2f, 3f, 4f);
```

Assign data to the attribute variable spevified by the location.


