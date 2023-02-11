# VRoid Tips and Exporting.
To get started, make sure you have a VRoid character created and ready for export.

> **QUEST ONLY:** Make sure your VRoid avatar has the following changes:
> - Eyebrows and eyeliner disabled.
> - Eyebrows and eyeliner painted on the face.
> - Combined iris and eye highlights.
> - Alphas clamped on tops and bottoms.

## Exporting
In VRoidStudio, click on `Export > Export as VRM`. On this screen you'll see a `Export Info` panel in the top right with a polygon count.
We want to reduce that number to the target on our platform (see [performance rank](https://docs.vrchat.com/docs/avatar-performance-ranking-system)) 
without making large sacrefices to quality.

Under the `Reduce Polygons` menu, the `Delete Transparent Mesh` checkbox should be checked for both platforms. You can reduce the polygons by increasing the sliders
below from 0 to 100. Typical values will look like:
```
Hair Smoothness: 10
Hair: 10
Face: 20
Body: 20
Outfit: 20
```
This may need to be increased to hit the target polygons. It is advised to increase `Face`, `Body`, and `Outfit` more than the others. Once ready you can click on 
`Export` and export it into a folder for the target platform.

### [NEXT STEP](../blender/)
