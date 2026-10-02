# Color Independent Word Segmentation From Transcribed Bangla Passages

Code for the EICT 2023 paper by Faias Satter, Noor Masrur and Sk. Md. Masudul Ahsan.

[arXiv](https://arxiv.org/abs/2610.01191) · [IEEE](https://doi.org/10.1109/EICT61409.2023.10427730) · [Thesis](https://github.com/FaiasPromit/Optical-Character-Recognition-From-Handwritten-Bangla-Texts)

## How to run

1. Use Python 3.12 and install `requirements.txt` in a virtual environment. Open the notebook in Jupyter, VS Code or Colab.
2. Edit the configuration cell. Set `USE_GOOGLE_DRIVE = True` for Google Drive in Colab; otherwise use local paths.
3. Set `PARAGRAPH_DIR` to the folder containing the paragraph BMP images and choose an empty `OUTPUT_DIR`.
4. Run the cells in order. The default selection processes the included `B022.bmp` and `B023.bmp` samples.

Word crops are saved under `OUTPUT_DIR/Word_Outputs`, with boxed previews and a JSON count summary alongside. Choose a new output folder when rerunning.

For all 80 paragraphs, download [PromitoLipi1.1](https://data.mendeley.com/datasets/fnw59h7y89/2), update `PARAGRAPH_DIR`, and set `IMAGE_NUMBERS = range(1, 81)`.

The `sortit()` reading-order implementation is not included, so crop numbering does not represent paragraph reading order.

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
