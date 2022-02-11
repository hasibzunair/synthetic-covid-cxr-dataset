# Synthetic COVID-19 Chest X-ray Dataset for Computer-Aided Diagnosis

This repository hosts dataset for our ICML 2021 Workshop on Computational Biology (WCB) paper. A more detailed version titled *Synthesis of COVID-19 Chest X-rays using Unpaired Image-to-Image Translation* is published in the Journal of Social Network Analysis and Mining (SNAM), Special Issue on Tackling COVID-19 Infodemic.

## Resources
* [ICML 2021 WCB Paper](https://icml-compbio.github.io/2021/papers/WCBICML2021_paper_13.pdf)
* [SNAM Journal Paper](https://link.springer.com/article/10.1007/s13278-021-00731-5)
* [arXiv](https://arxiv.org/abs/2106.09759)

The dataset consists of 21,295 synthetic COVID-19 chest X-ray images generated using [this](https://github.com/hasibzunair/adversarial-lesions) algorithm. Dataset is available at this [link](https://github.com/hasibzunair/synthetic-covid-cxr-dataset/releases/tag/v0.1).

<p align="center">
  <a href="#"><img src="./media/model.png"/></a> <br />
  <em> 
    Figure 1. Illustration of the data generation process based on unpaired image-to-image translation. Chest X-ray images are translated from Non-COVID-19 (i.e. Normal or Pneumonia) to COVID-19 and then back to Non-COVID-19 via cycle-consistency
    </em>
</p>

Here's a video of the learning in progress. Top row (Normal CXR, Translated COVID-19 CXR, Reconstructed Normal CXR), bottom row (COVID-19 CXR, Translated Normal CXR, Reconstructed COVID-19 CXR).

<p align="center">
  <a href="#"><img src="./media/training.gif"/></a> <br />
</p>

## Citation
If you use this dataset in your scientific work, please cite the following:
```bibtex
@article{zunair2021synthesis,
  title={Synthesis of {COVID}-19 chest {X}-rays using unpaired image-to-image translation},
  author={Zunair, Hasib and Hamza, A Ben},
  journal={Social Network Analysis and Mining},
  volume={11},
  number={1},
  pages={1--12},
  year={2021},
  publisher={Springer}
}
```

## Result highlights

<p align="center">
  <a href="#"><img src="./media/results.png"></a> <br />
</p>

## Acknowledgements

The synthetic dataset was generated using [https://github.com/hasibzunair/adversarial-lesions](https://github.com/hasibzunair/adversarial-lesions).

<img src="./media/meme.jpeg" width="300">
