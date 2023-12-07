# [**CellFormer-A-DaViT-Transformer-based-method-for-Nuclei-Segmentation**]
![](./overview.png)
#### Abstract
Automated analysis of microscopic pictures in computer-aided clinical support systems has difficulty identifying cell nuclei inside nuclei. Models based on the U-Net network, its derivatives or transformers, and their combinations have been proposed to segment cell nuclei, with positive results. However, these techniques omitted a number of details vital to simulating the regional appearance of the cell nucleus or missing a high-level representation of features for location dependence during decoding. For overcoming these limitations, the CellFormer network has been recommended in this research. With CellFormer, an encoder-decoder architecture, both the encoder and the decoder branches may mimic a long-range knowledge of semantics.
The encoder is a compact architecture built on transformers that describe global semantic linkages at different data levels. An AAMC module that we suggested along with the design to learn advanced features to enhance the feature representation is used by the decoder, which is an extended network topology, to convey data from the decoder.  In order to improve the boundaries of nuclear items on the global map for precise segmentation, an MSFB block with a novel bypass connection mechanism has been introduced. Through cell segmentation datasets such as GlaS and Data Science Bowl 2018, we assess the performance of this suggested architecture. The findings were far better than we had anticipated in the area of biomedical image segmentation.
## Datasets
Our paper using two datasets:
- Data Science Bowl 2018: 80% for training, 20 % for validation [Link data](https://www.kaggle.com/c/data-science-bowl-2018)

- Gland Segmentation [Link data](https://warwick.ac.uk/fac/cross_fac/tia/data/glascontest)

_All images in experiments resized to 256x256_


