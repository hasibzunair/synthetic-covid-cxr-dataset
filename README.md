# Synthesis of COVID-19 Chest X-rays using Unpaired Image-to-Image Translation [[arXiv](https://arxiv.org/abs/2010.10266)]

Dataset is available [here](https://github.com/hasibzunair/synthetic-covid-cxr-dataset/releases/tag/v0.1).

<p align="center">
  <a href="#"><img src="./media/synthetic.jpg"></a> <br />
</p>

This repository is part of the supplementary materials for our paper titled *Synthesis of COVID-19 Chest X-rays using Unpaired Image-to-Image Translation* accepted for publication in the Journal of 
Social Network Analysis and Mining (SNAM).

## Dataset Details

The dataset consists of 21,295 synthetic COVID-19 chest X-ray images. Images are generated using an unsupervised domain adaptation approach by leveraging class conditioning and adversarial training from source datasets [RSNA Kaggle Dataset](https://academictorrents.com/details/95588a735c9ae4d123f3ca408e56570409bcf2a9) and [COVID-19 Image Data Collection](https://github.com/ieee8023/covid-chestxray-dataset). Implementation of the algorithm is available [here](https://github.com/hasibzunair/adversarial-lesions).

<p align="center">
  <a href="#"><img src="./media/xray.png" height=600/></a> <br />
  <em> 
    Figure 1. Given any two unordered image collections, the generative algorithm learns to automatically translate an image from one category to another. Top: Normal (left) to COVID-19 (right). Bottom: Pneumonia (left) to COVID-19 (right). Subtle visual changes can be observed in the translated images due
to low inter-class variation.
    </em>
</p>

## Result highlights

<p align="center">
  <a href="#"><img src="./media/results.png"></a> <br />
</p>

## Citation
If you use this dataset in your scientific work, please cite the following:
```bibtex
@article{zunair2020synthesis,
  title={Synthesis of COVID-19 Chest X-rays using Unpaired Image-to-Image Translation},
  author={Zunair, Hasib and Hamza, A Ben},
  journal={arXiv preprint arXiv:2010.10266},
  year={2020}
}

@article{zunair2020melanoma,
  title={Melanoma detection using adversarial training and deep transfer learning},
  author={Zunair, Hasib and Hamza, A Ben},
  journal={Physics in Medicine \& Biology},
  year={2020},
  publisher={IOP Publishing}
}
```






