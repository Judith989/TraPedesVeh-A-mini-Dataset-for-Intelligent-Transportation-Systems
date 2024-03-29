# TraPedesVeh
This repository contains the TraPedesVeh mini dataset which is a collection of annotated images containing vehicles, traffic signs and pedestrians. It was first introduced in the paper titled "State-of-the-Art Object Detectors for Vehicle, Pedestrian, and Traffic Sign Detection for Smart Parking Systems", which was presented at the International Conference on Information and Communication Technology Convergence (ICTC2022), Jeju, South Korea. 


<img src="https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test/11.png" width="144"> <img src="https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test/1.png" width="144"> <img src="https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test/12.jpg" width="144"> <img src="https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test/13.jpg" width="144"> <img src="https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test/14.jpg" width="144"> 


## Dataset Description
The dataset was built by collecting random images from the internet, using the keywords: traffic signs, vehicles and pedestrians. A total of 230 different images were collected. The annotation of images was done manually using a graphical anotation tool named [Labelimg](https://github.com/tzutalin/labelImg). As illustrated in the table below, the annotation process produced a total of 938 annotated objects, for 7 different classes of objects. The [Labelimg](https://github.com/tzutalin/labelImg) program generates an XML file for each of the images annotated.

![alt text](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/dataset-stat.jpg)

The [train](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/tree/main/train) folder contains 146 annotated images and XML files, and the [test](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/tree/main/test) folder contains 46 annotated images and XML files.

Three other files are included in this repository: [test.tfrecord](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/test.tfrecord) contains the test images, [train.tfrecord](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/train.tfrecord) contains the training images, and [label_map.pbtxt](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/label_map.pbtxt) contains the labels. These will be very useful when training on object detection models that support tfrecord formats. 

The Tfrecord files were results from an augmented version of the original dataset. As a result, the training tfrecord file contains 501 images, while the test file contains 61 images. 

## Abstract



## Paper


## Authors
Judith Nkechinyere Njoku∗, Goodness Oluchi Anyanwu†, Ikechi Saviour Igboanusi†, Cosmas Ifeanyi Nwakanma∗, and Dong-Seong Kim†

## Citation
If you use this dataset in your research, please cite this repository. or cite this paper:

"J. N. Njoku, G. O. Anyanwu, I. S. Igboanusi, C. I. Nwakanma, J. -M. Lee and D. -S. Kim, "State-of-the-Art Object Detectors for Vehicle, Pedestrian, and Traffic Sign Detection for Smart Parking Systems," 2022 13th International Conference on Information and Communication Technology Convergence (ICTC), 2022, pp. 1585-1590, doi: 10.1109/ICTC55196.2022.9952856."




## License 
Creative Commons Zero v1.0 Universal [Link](https://github.com/Judith989/TraPedesVeh-A-mini-Dataset-for-Intelligent-Transportation-Systems/blob/main/LICENSE)
