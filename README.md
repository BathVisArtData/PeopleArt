#People-Art dataset

The People-Art dataset is a dataset of images from photos and artwork, with ground truth bounding boxes for people. The aim is to address the problem of detecting objects in images other than photographs. The reason for labelling people is that (we observe that) they occur more frequently than any other class.

The dataset contains the following:
* Images divided into 43 depiction styles: 41 styles are from [WikiArt.org](http://www.wikiart.org); photos are from [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/); cartoons from google searches.
* Labellings of people compatible with [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/) format, with some differences (see below)

The dataset was originally produced by [Hongping Cai](http://www.bristol.ac.uk/engineering/people/372003) and [Qi Wu](http://www.adelaide.edu.au/directory/qi.wu01) while working under [Peter Hall](http://www.cs.bath.ac.uk/~pmh/start/home.html) at the University of Bath.

## Labellings
The labellings of people are compatible with [PASCAL VOC](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/) format except for the following differences:
* The list of images is in the Annotations directory, as people_{train/val/test/trainval}.txt e.g. Annotations/people_train.txt. All images are either positive (at least one person) or negative (no people present)
* Images and Annotations lie in a sub-directory, e.g. JPEGImages/Cubism/pablo-picasso_algerian-women-delacroix-1955.jpg and Annotations/Cubism/pablo-picasso_algerian-women-delacroix-1955.jpg.xml
* Only images which are positive have xml annotation files

## Copyright
Many of the images are subject to copyright. These are provided only for "data mining for non-commercial research" or other "fair dealing" [(UK Guidance)](https://www.gov.uk/guidance/exceptions-to-copyright).

## Publications
The dataset [v2](https://github.com/nwestlake/people-art/releases/tag/v2) features in [The Cross-Depiction Problem: Computer Vision Algorithms for Recognising Objects in Artwork and in Photographs (arXiv pre-print)](https://arxiv.org/abs/1505.00110) and  [You only look once: Unified, real-time object detection (arXiv pre-print)](http://arxiv.org/abs/1506.02640).

The dataset [v2.1](https://github.com/nwestlake/people-art/releases/tag/v2.1) features in [Detecting People in Artwork with CNNs](http://link.springer.com/chapter/10.1007/978-3-319-46604-0_57).

If you wish to cite the dataset, please use the following [citation](citation.bib).
