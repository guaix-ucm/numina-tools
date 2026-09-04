# Mosaicking

## measure_xy_offset_2dimages

This script determines (X,Y) offsets between two 2D images using
cross-correlation.

```{include} files/help_numina-measure_xy_offset_2dimages.md
```

The inputs are two 2D images (numpy arrays) with the same dimensions.

The computed (X,Y) offsets indicate how much the second image is shifted
with respect to the first image. The offsets are returned in pixels.

The input images can be pre-processed by subtracting the median background
and/or rescaling to the range [0, 1].

NaN values in the input images are replaced with zeros before computing the
cross-correlation.

It is possible to use `--test` mode to create synthetic images with a known
offset, which can be used to validate the offset measurement. The synthetic
images can also be saved to FITS files for further analysis.

Usage examples:

```console
(venv_numina) $ numina-measure_xy_offset_2dimages \
  --test \
  --subtract-background --rescale-to-01 --plots
```

```console
(venv_numina) $ numina-measure_xy_offset_2dimages \
  --image1 image1.fits \
  --image2 image2.fits \
  --subtract-background --rescale-to-01 --plots
```

## extract_2d_slice_from_3d_cube

This script extracts a 2D section from a 3D FITS image. It allows specifying
the axis to collapse and the interval (pixel range) along that axis.

```{include} files/help_numina-extract_2d_slice_from_3d_cube.md
```

## generate_mosaic_of_2d_images

This script generates a mosaic of 2D images from a list of 2D FITS files.

```{include} files/help_numina-generate_mosaic_of_2d_images.md
```

## generate_mosaic_of_3d_cubes

This script generates a mosaic of 3D data cubes from a list of 3D FITS files.

- It is possible to use arguments to fix the desired outupt celestial 2D WCS,
  as well as the output `CRVAL3` and `CDELT3` parameters that define the output
  linear wavelength sampling.

- If the input is a single 3D FITS cube, the code can be used to resample the
  initial cube with different values of `CRVAL3` and `CDELT3`. In that case, it
  is recommended to use interp as the reprojection method to avoid the default
  Gaussian kernel used when the reprojection method is `adaptive`). 

```{include} files/help_numina-generate_mosaic_of_3d_cubes.md
```

