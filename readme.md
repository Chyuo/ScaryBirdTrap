Bird Detector (Beta)

This model is used to detect a birds and detect whats not a bird.


## The Algorithm
The algorithm is giving an image of either a bird model or a Non bird model. example: Robin, hawk, and crow. Cat, dog and lizards. you input the image that is in the test folder and it will read and classify the image.
## Running this project

1. Open putty and connect to Jetson nano through SSD
2. Connect to your Jetson Nano via VSCODE. 
3.Ensure that you have the proper things installed. The Renet18.onnx and all others like that - the ones that say resnet18.onnx and the final_project2.py. Also, esure that you have the labels.txt file.
5. enter docker container (Jetson-inference/python/training/classification$)
6. Then run this code  Type (imagenet.py --model=$NET/resnet18.onnx --input_blob=input_0 --output_blob=output_0 --labels=$DATASET/labels.txt $DATASET/test/b1.jpg bird.jpg)
7. A image should pop up in VScode inthe classification folder under (.gitignore)
8. And Click to display image.
(video link)
