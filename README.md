GLAPI
===============

```
gl.clearColor(red, green, blue, alpha)
```

Specify the clear color for the drawing area.

```
gl.clear(buffer)
```

Clear the specified buffer to preset values.In the case of a color buffer, the value specified by **gl.clearColor()** is used.

example:
**gl.clear(gl.COLOR_BUFFER_BIT);**

