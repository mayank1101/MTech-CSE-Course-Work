# Pathology-Region SSIM Analysis

This experiment investigates image similarity specifically within a segmented tumor region instead of over the full image.

## Method

1. Use the tumor mask to isolate the region of interest.
2. Flatten the masked arrays.
3. Select pixels belonging to the nonzero mask region.
4. Compute SSIM-related values for the corresponding original and super-resolved pixels.

The implementation and visual analysis are in [`pixel-wise-ssim.ipynb`](pixel-wise-ssim.ipynb).

## Interpretation note

Standard SSIM is defined over local image windows and incorporates spatial structure. Flattening masked pixels changes that spatial interpretation, so this notebook should be treated as an exploratory region-restricted metric calculation rather than a drop-in replacement for conventional image-level SSIM.

## References

- [SSIM-PyTorch example](https://github.com/pranjaldatta/SSIM-PyTorch/blob/master/SSIM_notebook.ipynb)
- [PSNR and SSIM notes](https://cvnote.ddlee.cc/2019/09/12/psnr-ssim-python)
