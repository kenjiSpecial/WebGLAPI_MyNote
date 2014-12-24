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
