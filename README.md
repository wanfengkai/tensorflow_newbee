# tensorflow_newbee
## lab3 is for skin cancer detection
This read csv file as input to train alexnet. Only help you to get through how to feed data in tensorflow.
## unet_lung_seg is for lung segmentation in __JSRT__ dataset with tensorflow.

I play around with tFrecords so that there will be no limitaiton wrt image file format. You can get the mask from https://www.isi.uu.nl/Research/Databases/SCR/download.php.
## unet_nodule_tfrecords_Can_get_nodule_posiiton.ipynb is for lung nodule detection. 
This can ge the posiiton of the suspicious lung nodules in one image and store the coordinate in txt for others to use.

This recall is 83%, precision is 38% on test dataset.
## unet_10_fold_nodule_segmentation.ipnb is for lung nodule detection and segmentation
This use 10 fold cross validation and it's able to get recall and precision automatically.
