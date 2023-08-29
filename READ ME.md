1. Install python 3.6
2. Install Anaconda software (which will be used to download Tensorflow)
3. Install Microsoft Visual Studio together with its developer tools
4. Install a Compiler e.g Pycharm for code editing and running(For our case we have Microsoft Visual Studio)
5. Open the folder with the project via the command prompt and install the requirements in the text document (requirements.txt) via the pip command
•	pip install -r requirements.txt 
-it will install the necessary requirements to help build the environment for tensorflow.


6. Open Anaconda prompt to install tensorflow
• type the following command
 	conda create -n tensorflow python=3.6

• next type the following command
conda activate tensorflow
It creates a virtual environments for tensorflow and the next route command with tensoflow enclosed in brackets (tensorflow)

•	Now install the tensorflow  via the following commands
 
	pip install --ignore-installed --upgrade tensorflow
	(needs around 450 GB to download and install tensors)

	pip install --ignore-installed --upgrade tensorflow-gpu 
	(450 GB needed)
7. You have now installed tensorflow. Open Visual Studio and Open the whole folder with your project. First run the Train python script. It opens the command prompt and outputs the results as the machine trains.
8. After the training is complete now run the Detection script, it opens the Web cam and starts a video stream. Make sure you are in a well-lit place (not too bright and not too dark)
If you are in front of the camera it will immediately detect whether you are wearing a mask or not.
