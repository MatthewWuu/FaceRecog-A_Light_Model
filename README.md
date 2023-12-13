# Light-weight model of Face_recognition(under the constrain of low volumn's dataset)
--------------------------------
## Preface


This is like a cozy little deep-learning adventure for beginners in the realm of face recognition. We dabbled with PCA to shrink down those face images and played around with a bunch of NCC models. Also, we threw in a fancy comparative analysis and report, comparing the good ol' CNN with the pre-trained FaceNet model by the legendary Tanai, H. Fun times! 

_Addapted from our coursework of G0191-XMUM(given by Prof.Wang Han)._

## Brief Introduction of the Work


Nowadays, face recognition is able to achieve high state of the art accuracy through Deep Learning algorithms such as Convolutional Neural Networks or Vision Transformers *(Dosovitskiy et al.,/ 2021)*. However, Deep Learning methods usually requires a large amount of dataset, numbering in the thousands to millions of datasets in order to prevent overfitting *(Seguin, 2017)*. 

Since we do not have access to this large amount of dataset, a better way is to use a simpler Machine Learning classification model such as Nearest Centre Classifier. Since the models are simpler and not suitable to handle complex dataset such as face images, we can use the Eigenface approach *(Turk & Pentland, 1991)*. We first apply Principal Component Analysis (PCA) to lower the dimensions of the faces. Once the lower dimension eigenfaces are generated from the PCA method, we use these as training data for the Nearest Centre Classifier. This will require less computational power and can be done in a shorter time *(Lee, 2022)*. The trade-off of this method is **reduction in accuracy due to the information loss when compressing**. Hence, the purpose of this report is to design and train three different types of face recognition systems and compare their performance. 

**For details, please jump into the jupyter file under the same directory ;)  **


