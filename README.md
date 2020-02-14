# Artemis
## Category - Software
## Problem No.- NM404
## Organisation - ISRO (Indian Space Research Organisation)
## Problem Statement - Size Invariant Ship detection from SAR Images

You can use the satellite images given in the repo for the validation of the model.Or you can also use any google earth image for the same purpose.The model works great on all google earth images.

WEBSITE DETAILS
Username - "admin"
Password - "admin"

Pass Key - "ARTEMIS" (FOR SIGNUP PURPOSE)

WEBSITE LINK : http://teamartemis.club
Hosted on Microsoft Azure.

## Installation Documentation
Youtube Video Link : https://youtu.be/dJGfQYUTWYg (Installation and Demo)

Enter username and password of of your github account which has access to this repo when asked:

	$ git clone https://github.com/gauravv0412/artemis.git
	
![](Screenshots/1.png)

	$ cd artemis

	$ sudo apt-get install virtualenv

	$ virtualenv env

	$ source env/bin/activate
	
![](Screenshots/2.png)

	$ sudo apt-get install python3.6

	$ sudo apt-get install python3-pip

	$ pip3 install -r requirements.txt
	
![](Screenshots/3.png)

	$ python3 manage.py makemigrations

	$ python3 manage.py migrate
	
![](Screenshots/4.png)

	$ pip3 install opencv-python
	
![](Screenshots/5.png)

	$ sudo su

	$ apt update && apt install -y libsm6 libxext6
	
![](Screenshots/6.png)

	$ sudo apt-get install libxrender1

	$ exit
	
![](Screenshots/7.png)

	$ cd home/model/SIH5/model/darknet/

	$ wget https://www.dropbox.com/s/55ykehj9kra2stt/yolov3-ship_1200.weights?dl=0 -O yolov3-ship_1200.weights
	
![](Screenshots/8.png)

	$ make
	
![](Screenshots/9.png)

get back to artemis directory by executing next command 5 times

	$ cd ..

	$ cd ..

	$ cd ..

	$ cd ..

	$ cd ..
	
![](Screenshots/10.png)

to launch server execute the following

	$ python3 manage.py runserver
	
![](Screenshots/11.png)

go to browser and type http://127.0.0.1:8000/

![](Screenshots/12.png)
