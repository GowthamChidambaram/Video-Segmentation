Read Me


Step1:

Install the packages given below:

		OpenCV 3.2
		matplotlib==2.0.0
		numpy==1.12.1
		scipy==0.19.0
		torch==0.4.1
		torchvision==0.2.0
		tqdm==4.11.2
		pydensecrf
		protobuf
		tensorboardX
Step2:
	Specify the path of dataset ,model name,and other parameters in 	corresponding configuration file
Step3:
	Run “train.py” with corresponding configuration file
         The model will be trained and the model will be stored in runs 	folder
Step4:
	Run “validate.py” with pascal voc2007 dataset
         Based on the results(accuracy) change the hyperparameters to get 	better result
Step5:
	Run “Video to image.py” 
         The frames will be stored in a folder
Step6:
	Run “test.py” with input
	Input will be the above mentioned folder containing the frames 	of the video
	Output will the segmented images of the given frames 
Step7:
	Run “frames_to_video.py” 
	Input will be the segmented images 
	Output will be a video segmentation of the given video
	 

