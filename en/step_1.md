## Colour in p5

The `p5` `color()` function expects three numbers: one each for red, green, and blue.

```python
sky = color(92, 204, 206) #Red = 92, Green = 204, Blue = 206
```

You can use a colour to fill a shape with the `fill()` function. `fill()` changes every shape drawn after it.

```python
grass = color(149, 212, 122)
fill(grass)
rect(0, 250, 400, 150) # This shape will be filled with the colour
```

To remove fills completely, call `no_fill()` before drawing your shape(s).

You can set a colour for the border around a shape with the `stroke()` function:

```python
white = color(255, 255, 255)
stroke(white)
rect(0, 250, 400, 150) # This shape will have a white border
```
