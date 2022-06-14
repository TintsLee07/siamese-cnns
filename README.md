# Facial Recognition Through Siamese Convolutional Neural Networks
## This repo contains a research paper and code used to generate results on Facial Recognition Through Siamese CNNs.
# Abstract
## Facial images offer a reliable means of physical biometric identification. However, image modularities,
geometric distortions, partial deformations, and obstructions could easily lead to false positives or false
negatives. This paper explores the viability of a Patch-based Siamese CNN for region-specific extraction in
situations described above. The idea is to create a facial recognition model that will still perform even when
only partial facial information is available. We extract nine patches and create nine Patch-specific models. We
explore the accuracy of three Patch-based models that uses different combinations of Patch-specific sub-models
against one that uses a global facial image. Training and testing are performed on the AT&T face dataset.
Experimental work shows that carefully combined Patch-Specific CNNs can perform better than a Global
CNN. The Global CNN classified image pairs with an EER of 0.090. A Patch-based Siamese CNN of all nine
patches achieved an EER of 0.045. Two Patch-based Siamese CNNs, one with carefully chosen Patch-specific
sub-models and the other with random Patch-specific sub-models, achieved an EER of 0.037 and 0.098,
respectively.


