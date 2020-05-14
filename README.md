## Synthetic Image Dataset of COVID-19 Chest X-rays 

<p align="center">
  <a href="#"><img src="./media/synthetic.jpg"></a> <br />
</p>

A public dataset for synthetic COVID-19 chest X-ray cases.

## Data Generation Pipeline


Contains 21,295 synthetic COVID-19 chest X-ray images. Original data from [RSNA Kaggle Dataset](https://academictorrents.com/details/95588a735c9ae4d123f3ca408e56570409bcf2a9) and [COVID-19 Image Data Collection](https://github.com/ieee8023/covid-chestxray-dataset) which are publicly avaiable and can be downloaded from the URLs.

<p align="center">
  <a href="#"><img src="./media/xray.png" height=600/></a> <br />
  <em> 
    Figure 1. Given any two unordered image collections, the generative algorithm learns to automatically translate an image from one  into  the  other: (left) Normal to (right) COVID-19; (left) Pneumonia to (right) COVID-19.
    </em>
</p>


The synthetic COVID-19 CXR images are generated using this conditional image synthesis [algorithm](https://github.com/hasibzunair/adversarial-lesions), validation study [here](https://arxiv.org/abs/2004.06824).


## Preliminary results


<p align="center">
  <a href="#"><img src="./media/umap.png"></a> <br />
  <em> 
    Figure 2. Two-dimensional UMAP of features to determine the distribution of original and synthetic examples. Both both tasks it
can be seen that the synthetic samples are in a different distribution in the feature space which enables a decision boundary among
the classes.
    </em>
</p>



## Citation

## Acknowledgements






