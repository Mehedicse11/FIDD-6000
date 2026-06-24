## FIDD-6000: A Benchmark Dataset for Image Forgery Detection and Localization on Social Media Images

## Overview

**FIDD-6000 (Forgery Image Detection Dataset - 6000)** is a large-scale benchmark dataset developed for research in **image forgery detection and localization** under realistic social media conditions. The dataset was introduced to address the growing challenge of detecting manipulated images that have undergone platform-induced transformations such as compression, resizing, and filtering, which often conceal forensic traces.
 FIDD-6000 contains both authentic and manipulated social media images with **pixel-level ground-truth annotations**, enabling researchers to evaluate not only whether an image is forged but also where the tampered regions are located.


## Availability

* **Kaggle Dataset:** https://www.kaggle.com/datasets/mehedi110223/fidd-6000

---
---

## Dataset Statistics

* **Dataset Name:** FIDD-6000
* **Total Images:** 6,000
* **Authentic Images:** 1,000
* **Manipulated Images:** 5,000
* **Forgery Categories:**

  * Splicing
  * Copy-Move
  * Retouching
* **Ground-Truth Masks:** Pixel-level annotations for all manipulated images
* **Image Format:** JPEG (.jpg)
* **Image Resolution:** Various resolutions
* **Post-Processing Conditions:** Images include realistic social media transformations such as compression and resizing.

---

## Dataset Structure

```text
FIDD-6000/
├── Authentic/
│   ├── image_0001.jpg
│   ├── image_0002.jpg
│   └── ...
│
├── Manipulated/
│   ├── image_1001.jpg
│   ├── image_1002.jpg
│   └── ...
│
├── Masks/
│   ├── mask_1001.png
│   ├── mask_1002.png
│   └── ...
│
└── README.md
```

> Each manipulated image has a corresponding pixel-level ground-truth mask indicating the tampered regions.

---

## Intended Use

FIDD-6000 is designed for:

* Image forgery detection.
* Image forgery localization.
* Binary classification of authentic versus manipulated images.
* Benchmarking image forensic algorithms.
* Training and evaluating deep learning models.
* Performance evaluation under realistic social media degradation.
* Comparative studies of state-of-the-art forgery detection techniques.
* Academic research and educational purposes.

---

## Benchmark Evaluation

To demonstrate the challenges posed by social media image manipulations, the original study evaluated **15 state-of-the-art image forgery localization methods** on FIDD-6000, including approaches based on:

* JPEG compression artifacts,
* Sensor-noise analysis,
* Error Level Analysis (ELA), and
* Other forensic feature extraction techniques.

Experimental results revealed that existing methods perform poorly on FIDD-6000, highlighting the need for more robust and advanced approaches capable of handling social media-specific transformations.

---

## Applications

Potential applications include:

* Social media content verification,
* Digital image forensics,
* Fake news mitigation,
* Trustworthy multimedia systems,
* Content moderation,
* Media authenticity assessment,
* Development of next-generation forgery detection frameworks.

---

## Citation

If you use this dataset in your research, please cite the following publication:

```bibtex
@article{Rana2026FIDD6000,
  title     = {A Benchmark for Image Forgery Detection and Localization on Social Media Images},
  author    = {Rana, Md. Mehedi Rahman and Rahman, Md. Anisur and Talukder, Kamrul Hasan and Galib, Syed Md. and Siddique, Nazmul},
  journal   = {Journal of Sensor and Actuator Networks},
  volume    = {15},
  number    = {3},
  pages     = {1--34},
  year      = {2026},
  publisher = {MDPI},
  doi       = {10.3390/jsan15030040},
  issn      = {2224-2708}
}
```

### Publication

Rana, M. M. R., Rahman, M. A., Talukder, K. H., Galib, S. M., & Siddique, N. (2026). *A Benchmark for Image Forgery Detection and Localization on Social Media Images*. **Journal of Sensor and Actuator Networks, 15**(3), 40. https://doi.org/10.3390/jsan15030040

---



## License

This dataset is released for **research and educational purposes**.

Users are responsible for ensuring compliance with applicable ethical guidelines and any licensing restrictions associated with original source materials used to construct the dataset.

---


---

## Contact

**Md. Mehedi Rahman Rana**
Department of Computer Science and Engineering (CSE)
Bangladesh Army University of Science and Technology (BAUST), Khulna, Bangladesh
mehediranacse11@gmail.com

For questions, suggestions, collaborations, or issue reporting, please open an issue in this repository.

---

