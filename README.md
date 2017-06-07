# Classifying Wildlife Camera Trap Images for Conservation International’s Tropical Ecology Assessment and Monitoring Network

Monitoring wildlife species in a non-intrusive and cost-effective manner has been made possible through camera trapping methods, which employ cameras set off by sensors to take bursts of images of animals in their natural habitat. The Tropical Ecology Assessment and Monitoring (TEAM) Network managed by Conservation International (CI) monitors long-term trends in biodiversity, land cover change, climate, and ecosystem services in tropical forests. The network has built a system of camera trap stations within sixteen tropical forest sites across Africa, Asia and Latin America that feed image data to experts at the regional hub field sites, which then make their way into an image repository at CI for further analysis and research.

This repo contains most of the files needed to replicate a method to classify the *Loxodonta* genus within the *Elephantidae* family of African elephants from camera trap image data using a simple classification pipeline: manual segmentation of images; feature extraction using SIFT; and classification using the Bag of Visual Words and linear SVM models.

Files in this repo:
- [Brief overview of the classification task](https://github.com/tonmcg/Classify-Terrestrial-Vertebrate/blob/master/Classifying%20Wildlife%20Camera%20Trap%20Images.pdf)
- [Setup, methods, and findings report](https://docs.google.com/document/d/1evtda_AZTxUkTjJItt7sfubWbpD199MSunjPySHX3h8)
- [Jupyter iPython Notebook](https://github.com/tonmcg/Classify-Terrestrial-Vertebrate/blob/master/Classifying%20Wildlife%20Camera%20Trap%20Images.ipynb)
- [Viewable version of the iPython notebook](https://nbviewer.jupyter.org/github/tonmcg/Classify-Terrestrial-Vertebrate/blob/master/Classifying%20Wildlife%20Camera%20Trap%20Images.ipynb)
- [Pre-cropped image files](https://github.com/tonmcg/Classify-Terrestrial-Vertebrate/tree/master/Loxodonta)
- [CalTech 101 Objects images used in training](https://github.com/tonmcg/Classify-Terrestrial-Vertebrate/tree/master/101_ObjectCategories)
