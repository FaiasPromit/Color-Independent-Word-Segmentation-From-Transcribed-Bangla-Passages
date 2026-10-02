# Color Independent Word Segmentation From Transcribed Bangla Passages

Code for the paper **"Color Independent Word Segmentation From Transcribed Bangla Passages"** (EICT 2023).

Paper: [IEEE](https://doi.org/10.1109/EICT61409.2023.10427730) · [arXiv](https://arxiv.org/abs/2610.01191)  
Thesis and related papers: [Optical Character Recognition From Handwritten Bangla Texts](https://github.com/FaiasPromit/Optical-Character-Recognition-From-Handwritten-Bangla-Texts)

The code segments words in smartphone photos of handwritten Bangla paragraphs, on any color of paper and ink, including images with shadows.

## How to run

The code runs in Google Colab.

1. Download the `Thesis-OCR` folder from this repository.
2. Upload it to the top level of your Google Drive (My Drive).
3. Open `Color Independent Word Segmentation From Transcribed Bangla Passages.ipynb` in Google Colab and run it.
4. The segmented words are saved in the `Words_Outputs` folder.

## Running on the full dataset

By default, the notebook processes only two sample images. To run it on all 80 paragraph images:

1. Download the PromitoLipi dataset from [Mendeley Data](https://data.mendeley.com/datasets/fnw59h7y89/2) and upload it to your Google Drive.
2. Replace the existing `PromitoLipi1.1` folder with the dataset's `PromitoLipi1.1` folder.
3. In the last cell of the notebook, change `for i in range(22,24):` to `for i in range(1,81):`.

## Citation

If you use this code, please cite:

F. Satter, N. Masrur and S. M. M. Ahsan, "Color Independent Word Segmentation From Transcribed Bangla Passages," *2023 6th International Conference on Electrical Information and Communication Technology (EICT)*, Khulna, Bangladesh, 2023, pp. 1-6, doi: 10.1109/EICT61409.2023.10427730.

```bibtex
@inproceedings{satter2023color,
  author    = {Satter, Faias and Masrur, Noor and Ahsan, Sk. Md. Masudul},
  title     = {Color Independent Word Segmentation From Transcribed Bangla Passages},
  booktitle = {2023 6th International Conference on Electrical Information and Communication Technology (EICT)},
  address   = {Khulna, Bangladesh},
  year      = {2023},
  pages     = {1--6},
  doi       = {10.1109/EICT61409.2023.10427730}
}
```
