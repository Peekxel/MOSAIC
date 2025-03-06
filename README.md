# MOSAIC: Morphological Single-cell Analysis with Integrated Conditioning

Welcome to **MOSAIC** (**Morphological Single-cell Analysis with Integrated Conditioning**), a diffusion-based approach for analyzing and translating single-cell microscopy images. By leveraging GenePT-style embeddings for genes and compounds, MOSAIC enables sophisticated conditioning of image generation, allowing researchers to visualize phenotypic changes associated with different genetic or chemical perturbations.

If you want to run **cell image translation experiments** using our pretrained model, visit our **live demo** where our model is hosted with a user-friendly interface.

## 🧬 MOSAIC Features

MOSAIC can be used to:
* Generate realistic single-cell images conditioned on gene or compound embeddings
* Translate between different cellular phenotypes
* Explore the effects of genetic or chemical perturbations on cell morphology
* Detect subtle phenotypic differences that may not be visible to the human eye

## 📚 Implementation Details

The model architecture is based on diffusion models with UNet backbones, incorporating frequency-aware image translation inspired by Gao et al.'s "Frequency-Controlled Diffusion Model for Versatile Text-Guided Image-to-Image Translation".

## 🧪 Dataset

MOSAIC was trained on 4 million single-cell images extracted from the JUMP Cell Gallery (CP0000). Each image was centered and processed to ensure consistent quality for training.

## 📂 Repository Contents

The main code is organized in the following structure:
* `scripts/train.ipynb`: Training pipeline for the MOSAIC diffusion model
* `scripts/inference.ipynb`: Examples of inference and image translation

## 📥 Pretrained Models and Embeddings

We provide pretrained model checkpoints and GenePT embeddings via Google Drive: Download Models and Embeddings



## 📝 Citations

If you use MOSAIC or any individual datasets, or publications, please cite the original studies as well as the MOSAIC:

```
@misc{MOSAIC,
  author = {Peekxel},
  title = {MOSAIC: Morphological Single-cell Analysis with Integrated Conditioning},
  year = {2025},
  url = {https://github.com/Peekxel/MOSAIC},
  version = {1.0.0}
}
```

## 📬 Contributing & Contact

If you would like to add a dataset to MOSAIC, please submit a **merge request** with the dataset details. For any inquiries, feel free to reach out via email at **thisfaraz@peek.art**.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.