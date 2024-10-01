# Introduction to Deep Learning project: Vision-Transformer-for-remote-sensing-image-segmentation
Group members: 
* Nguyễn Quốc Khánh	- 22BI13211
* Nguyễn Gia Bách	- 22BI13052
* Phùng Tiến Đạt	- 22BI13081
* Nguyễn Thị Hà Anh	- 22BI13029
* Nguyễn Đăng Nguyên - 22BI13340
* Giáp Đỗ Anh Minh	- 22BI13282

In this project, we used the Vision Transformer model for building segmentation task as our case study, which is required to correctly segment between building and non-building areas of the aerial images.\
The dataset used in this project is INRIA Aerial Image Labeling Dataset, which can be accessed through this link: https://project.inria.fr/aerialimagelabeling/ \
There are 2 models that we have experimented: 
* The first model was built and trained from scratch 
* In the second model, we used the pre-trained SegFormer model's weight mit-b0, which was pre-trained on a general segmentation dataset ADE20k and fine tuned to the INRIA dataset 
