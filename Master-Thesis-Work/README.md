# Quantitative Analysis of Super-Resolution on Medical Image Pathology

This directory archives the implementation work, evaluation artifacts, papers, and presentations for an M.Tech thesis conducted at IIT Jammu under the supervision of Prof. Harkeerat Kaur and Prof. Bakul Gohel.

## Research scope

The work evaluates how super-resolution affects both normal anatomy and pathological regions in medical images. It covers SRCNN, ESPCN, SRGAN, WDSR, and EDSR across brain-tumor MRI, breast-histopathology, diabetic-retinopathy, and chest X-ray imagery.

Evaluation uses RMSE, PSNR, SSIM, MS-SSIM, SCC, and VIFP. Disease-specific regions are evaluated separately, and the research hypothesis is assessed with the Mann-Whitney U test.

## Contents

- [`Implementation Work/`](Implementation%20Work/) contains model, denoising, disease-detection, dataset-analysis, and pixel-level SSIM notebooks, plus an SRGAN training script.
- [`kaggle_notebooks/`](kaggle_notebooks/) contains the Kaggle-oriented experiment and metric notebooks.
- [`statistical_test/`](statistical_test/) contains serialized metric data, JSON results, and statistical-analysis artifacts.
- [`Presentation/`](Presentation/) contains milestone presentations, the final presentation, and supporting figures.
- [`Research Papers Referenced/`](Research%20Papers%20Referenced/) contains papers consulted during the research.

The [final thesis presentation](Presentation/Thesis_Presentation%20-%20Final.pdf) summarizes the completed work.

## Working with the notebooks

The notebooks were created across different environments and use a mixture of TensorFlow/Keras, PyTorch, OpenCV, NumPy, pandas, SciPy, scikit-image, Matplotlib, Pillow, and `sewar`. There is no single pinned environment. Create a virtual environment and install only the packages required by the notebook being examined.

Many notebooks were originally run on Kaggle and refer to platform-specific input paths or external datasets. To reproduce an experiment, obtain the dataset from its original source and update those paths locally. Model training can require substantial memory, runtime, and GPU support.

## Data and security notes

- Generated images and metric outputs are retained because they form part of the research record.
- The repository does not contain every original dataset needed to rerun the experiments.
- Only load the committed `.pkl` files if you trust the repository; Python pickle data can execute code during deserialization.
- Medical-image experiments in this archive are research artifacts, not clinical software or medical advice.

## Rights and reuse

This directory does not include a separate license. Referenced papers, datasets, medical images, and other third-party material remain subject to their original terms.
