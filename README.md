## Bicubic interpolation Copy And Paste from wikipedia
https://en.wikipedia.org/wiki/Bicubic_interpolation

## demo
![demo](demo.gif)

## dependency
openframeworks 0.10.0

## sample code

```

// sample normalized u, v
// from X_SIZE, Y_SIZE data table
// data access function by std::function<float(int x, int y)> 
float value = bicubic_2d<float, float>(u, v, X_SIZE, Y_SIZE, [&](int x, int y) { return image[y][x]; });

```
