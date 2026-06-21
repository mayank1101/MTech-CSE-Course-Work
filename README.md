# Master's Course Work

A collection of coursework and thesis research from an M.Tech program, covering algorithms, mathematics, optimization, machine learning, deep learning, and medical-image super-resolution. The repository brings together lecture material, tutorials, assignments, reference texts, Jupyter notebooks, implementations, experiments, and research presentations.

> This is an academic archive rather than a single software project. Each course is self-contained and may have different tools, dependencies, and licensing terms.

## Courses

| Semester | Course | Code | Repository contents |
| --- | --- | --- | --- |
| 1 | [Advanced Data Structures and Algorithms](Advance-Data-Structures-and-Algorithms-CSL-006P1M/) | CSL006P1M | Lecture slides, assignment sheets, C++ lab solutions, test data, and notes on divide and conquer, greedy algorithms, dynamic programming, approximation algorithms, and NP theory. |
| 1 | [Linear Algebra](Linear-Algebra-CSD001P5M/) | CSD001P5M | 41 lecture PDFs, 11 tutorials, supplementary proof material, personal notes, and reference books. |
| 1 | [Probability and Statistics](Probability-and-Statistics-CSL003P1M/) | CSL003P1M | Assignment sheets and selected solutions, probability tables, solved problems, and reference books. |
| 2 | [Optimization Techniques](Optimization-Techniques/) | SC550 | Written assignments and a Jupyter implementation of the transportation problem; topics include linear programming, simplex methods, duality, assignment problems, and game theory. |
| 2 | [Pattern Recognition and Machine Learning](Pattern-Recognition-and-Machine-Learning-PRML/) | IT-542 | Lecture slides, mathematical notes, nine lab assignments, notebooks, a MATLAB exercise, and reference material covering classification, clustering, dimensionality reduction, regression, EM, and SVMs. |
| 3 | [Deep Learning](Deep-Learning-CSC004P5E/) | CSC004P5E | Theory and lab assignments on loss functions, gradient descent, computation graphs, neural networks, CNNs, RNNs, autoencoders, and GANs, plus a from-scratch neural-network/CNN group project. |

Each directory has its own README with additional course-specific details.

## Master's thesis

### [Quantitative Analysis of Super-Resolution on Medical Image Pathology](Master-Thesis-Work/)

The thesis evaluates how image super-resolution affects normal and pathological medical images. It compares SRCNN, ESPCN, SRGAN, WDSR, and EDSR across brain-tumor, breast-histopathology, diabetic-retinopathy, and chest X-ray imagery.

The directory includes:

- Model implementation and evaluation notebooks.
- Experiments with denoising autoencoders and disease detection.
- Image-quality analysis using RMSE, PSNR, SSIM, MS-SSIM, SCC, and VIFP.
- Region-specific analysis of disease pathology and Mann-Whitney U statistical testing.
- Serialized metrics, generated images, plots, thesis presentations, and referenced research papers.

## Repository layout

```text
.
├── Advance-Data-Structures-and-Algorithms-CSL-006P1M/
│   ├── Assignments/
│   ├── PPT/
│   └── lab/
├── Deep-Learning-CSC004P5E/
│   ├── DL-Course-Assignment/
│   ├── Lab Assignments/
│   └── Theory Assignments/
├── Linear-Algebra-CSD001P5M/
│   ├── Lectures/
│   ├── Tutorials/
│   ├── Tutorials Study Material/
│   ├── books/
│   └── my notes/
├── Master-Thesis-Work/
│   ├── Implementation Work/
│   ├── Presentation/
│   ├── Research Papers Referenced/
│   ├── kaggle_notebooks/
│   └── statistical_test/
├── Optimization-Techniques/
│   ├── Coding Assignments/
│   └── Online Assignments/
├── Pattern-Recognition-and-Machine-Learning-PRML/
│   ├── class/
│   ├── lab/
│   ├── lectures/
│   └── maths/
└── Probability-and-Statistics-CSL003P1M/
    ├── Assignment/
    └── ebooks/
```

## Using the coursework

Clone the repository and enter the course directory you want to explore:

```bash
git clone https://github.com/mayank1101/MTech-CSE-Course-Work.git
cd MTech-CSE-Course-Work
```

Most theory material only requires a PDF or presentation viewer. To work with the programming assignments, install the tools relevant to that course:

- A C++ compiler with C++11 support or newer for the algorithms labs.
- Python 3 and Jupyter Notebook or JupyterLab for the `.py` and `.ipynb` exercises.
- Common scientific Python packages used by the notebooks and scripts, including NumPy, pandas, SciPy, scikit-learn, scikit-image, and Matplotlib.
- Deep-learning and imaging packages used by the thesis notebooks, including TensorFlow/Keras, PyTorch, OpenCV, Pillow, and `sewar`. Individual notebooks use different frameworks, so install only the dependencies needed for the experiment you intend to run.
- MATLAB or GNU Octave for the PRML MATLAB exercise.

For example, a local Python environment can be prepared with:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyter numpy pandas scipy scikit-learn scikit-image matplotlib
jupyter lab
```

Dependencies are not pinned, and some material was created with older library versions. Minor compatibility changes may be needed when running it with current tooling. Thesis notebooks originally developed on Kaggle may also require dataset downloads and local path changes before execution.

## Notes

- Paths preserve the original course and assignment names, including spaces and historical spelling.
- The root `.gitignore` excludes new notebook checkpoints, Python bytecode, local environments, editor metadata, and common build products. Some historical generated files remain tracked in the archive; ignore rules do not remove files that are already committed.
- The thesis directory includes experimental outputs and serialized `.pkl` metric files. Only load pickle files from a trusted source.
- Solutions are provided for learning and reference. If you are currently enrolled in a related course, follow your institution's academic-integrity policy before consulting them.
- Large PDFs, books, and slides may be subject to their authors' or publishers' rights; their inclusion here does not change those rights.

## License

The Optimization Techniques, Pattern Recognition and Machine Learning, and Probability and Statistics directories each include an MIT License. The repository root and the other course and thesis directories do not currently include a license file. Third-party lecture notes, books, papers, slides, datasets, medical images, and other reference material remain subject to their original terms.
