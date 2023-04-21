# Object-Detection
Object detection is a supervised machine learning problem, which means one must train models on labeled examples. Each image in the training dataset must be accompanied with a file that includes the boundaries and classes of the objects it contains. Object detection networks bear much resemblance to image classification networks and use convolution layers to detect visual features. In fact, most object detection networks use an image classification CNN and repurpose it for object detection.


Aim:
Our main goal in this project is to ensure that it detects items from the given input image and can distinguish which object (i.e. cats and dogs) it is.


Project Description:
It is necessary for us to create a model that can detect objects. We will need between 1000 and 2000 photos of cats and dogs. Each image may feature a cat, a dog, or a combination of the two. So, basically the code that we have developed distinguishes the features and detects if the image belongs to a cat or a dog.


Purpose of The Project:
For Object detection, we're going to take a rather straightforward approach.
The goal is to get a deep neural network to generate a set of values that characterize an object detection situation (known as Object encodings). When you pass in two photographs of the same Object, the network should produce similar outputs (i.e., closer numbers) for both images, however when you pass in two images of different objects, the network should return drastically different outputs for both images.

This means that the neural network must be taught to recognize and calculate numbers based on distinct properties of an object. The neural network's output can be regarded of as an identifier for a specific object's - If you feed the neural network several photographs of the same thing, the output will be quite similar/close, but if you feed it different images of a different object, the result will be very different.

Details of Implementation:
1. To begin, we gathered all images of cats, dogs, and mixed pictures of both cats and dogs.
2. We started by labeling the photographs that merely included a cat as an item.
3. We next classified the photographs that solely had dogs as an object in them.
4. As we have pictures of cats and dogs consolidated, we named them separately to differentiate the contrast between both.
5. Utilizing information from named pictures and the real picture, work out picture encodings (numbers 	that portray the article).
6. Analyze the item encodings of known objects with those from test pictures to tell which article is in the image.
7. Additionally we sent the model on portable mobile, which shows the name of taken.
Proposed Method/Steps followed:
•	Setup Path.

•	Creating a Virtual Environment

•	Download TF Models Pretrained Models from Tensorflow Model Zoo and Install TFOD.

•	Create a Label Map.

•	Create TF records.

•	Copy Model Config to Training Folder.

•	Update Config for Transfer Learning.

•	Train the model

•	Evaluate the Model

•	Load Train Model from Checkpoint

•	Detect from an Image

•	Freezing the Graph


