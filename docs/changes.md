## Main changes

- general improvements to the `vedo` command line
- `colorcet` [colormaps](https://colorcet.holoviz.org) are directly usable in `vedo`. Check example `basic/mesh_custom.py`

---
### `base.py`
- corected bug on `diagonalSize()` returning a wrong value

---
### `addons.py`

---
### `colors.py`

---
### `mesh.py`
- `computeNormals()` is no more changing the nr of mesh points unless `featureAngle` is specified
    - added keywords: `featureAngle=None, consistency=True`
- `intersectWithLine()` can now return cell ids, not just points

---
### `plotter.py`

- improved automatic text management in `show("some text")`
- added `computeWorldPosition(point2d)` to get the 3d point in the scene from a screen 2d point

---
### `picture.py`
- added FFT and RFFT, added example `fft2d.py`
- can save `Picture` obj to file as jpg or png

---
### `pointcloud.py`

---
### `pyplot.py`

---
### `shapes.py`

---
### `volume.py`

---
### `utils.py`
- added `roundToDigit(x,p)`, round number x to significant digit


-------------------------

## New/Revised examples:
- `vedo -r koch_fractal`
- `vedo -r mesh_custom`
- `vedo -r fft2d`
- `vedo -r lines_intersect`





