Title : Accuracy comparison between filtered and unfiltered EMG signal in gesture recognition classification by using machine learning

Background
	The artificial intelligent for prosthetics limb control are being widely used in many field of research and application.[2] The advancement of the technology allow disable people to control over their prosthetic limbs after arm amputation. [1] The machine learning allow patient to control their limb more effectively with high accuracy.[3] The EMG signal are needed in machine learning to let machine recognize gesture pattern and translate it to limb motion according to the signal. The method require raw data to process to usable signal. Then, the feature extracting process will get detail of the signal. The machine learning will use this feature to classify it to different gesture.[2] The gesture data will control the prosthetic limbs according to user intention.[3] However, the method are complex and require many process from raw data to usable signal. In real signal data, the noise also generate in the process of acquiring the data.[5] The filtering technique are being use to remove noise from raw signal. The artificial intelligence can also use to remove noise and extract the signal from raw data.[4] However, the denoise process will also remove small part of the real signal. This study aim to compare the result in gesture accuracy between filtered signal and unfiltered signal in gesture recognition by using machine learning.

Objective
	To study the detail of the signal acquire from EMG raw data and increase the accuracy of hand gesture to use in prosthetic limbs

Method
	4-channel EMG electrode are being placed around the arm of the person in specific arrangement. The participants will require to move the hand in 4 different gesture for 2 second. The EMG data are being record. The raw data and filtered data. Then, use in neural network to classify the gesture and measure the accuracy. The raw data also use in neural network and compare the result against the first method.

This project include
	1. Project_signal_classification.ipynb
	2. README.md (This file)
	3. License.md
	4. Result.xlsx contain progress of accuracy on each epochs
	5. No database include, please download them yourself

Running the program
	1. Download EMG datasets from Mendeley data(Doi:10.17632/ckwc76xr2z.2)
	2. Place dataset in folder and edit your directory of dataset in notebook
	3. Run code Splitting Data from raw signal (to switch filtered signal to raw signal, please edit it in line of code)
	4. Run ANN to obtain accuracy result
	5. Edit your Text output directory in last cell
	6. Enjoy waiting
	
Result
	1. Filtered signal accuracy reach 100% very quickly
	2. Raw signal take more time however, even with 2000 epochs, the accuracy did not reach 100%
	
