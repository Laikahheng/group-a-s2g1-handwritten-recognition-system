# PROJECT OVERVIEW
## D. EXECUTING THE PROJECT
### Project Design and Coding
Flowchart Design:
<img src="assets/Flowchart_Diagram.png" width="30%">

Handwriting Recognition Implementation Example

## Description of the project coding implementation

Firstly, we will import some useful libraries. The library needed for handwritten recognition system are numpy and cv2. NumPy aims to provide an array object that is faster and compact than traditional Python lists.  Being an Open-Source library for deep learning and machine learning, TensorFlow plays a vital role in this handwritten recognition system. 

![image](https://user-images.githubusercontent.com/121591873/211891793-867aaa22-6f9f-4fa2-8e8d-c2954eb0e59b.png)

Next is to implement the architecture and structure of convolutional neural network (CNN). CNN has has three layers namely, convolutional, pooling, and a fully connected layer. It is a class of neural networks and processes data having a grid-like topology. The convolution layer is the building block of CNN carrying the main responsibility for computation of the handwritten recognition. 
![image](https://user-images.githubusercontent.com/121591873/211895073-1b824961-a0de-485e-a1f4-9c29f1aced46.png) 

In here we can see that the codes is experimenting by trying different number of layers and nodes where by it uses previous experience to choose the number of layers and nodes. More layers mean more depth, hence deep neural networks will perform better. 
![image](https://user-images.githubusercontent.com/121591873/211897040-19434e96-a32f-41f9-961e-b53bcb7cbf16.png)

This system uses is a deep Convolutional Recurrent NeuralNetwork (CRNN) inspired from the VGG16 architecture[5] used for image recognition. This is the implementation 
for text-line recognition of documents. We showed how to train such system with few labeled text-line data. Speciﬁcally, we proposed to bootstrap an incremental training procedure.

![image](https://user-images.githubusercontent.com/121591873/211899293-bd232e9b-948a-4d07-aa18-d201e4cfde7a.png)

Next is the training phase where to further enhance the performance of the system, we exploited the variability in the writing scale to augment the training set with text-line images at multiple scales. The training lines were ﬁrst classiﬁed into 3 classes (Large, Medium and Small) through Jenks natural breaks optimization algorithm.

![image](https://user-images.githubusercontent.com/121591873/211899860-a289464e-0aee-4103-884a-d6fb8517f5ae.png)

Lastly on to the testing phase, the test data were equalized in order to best ﬁt the core model of the system. The combination of the multi-scale trained system results on multi-scale test data has yielded the best results. 

![image](https://user-images.githubusercontent.com/121591873/211901252-ef0ff9b8-71ea-4e23-8ee0-3d49289d84f4.png)

### Project Result

![image](https://user-images.githubusercontent.com/121591873/211905291-d853463a-caa4-4376-a018-61ca0a36b4d8.png)


<br><br><br>
##### Next: [Project Closing](D-PROJECT_CLOSING.md)



