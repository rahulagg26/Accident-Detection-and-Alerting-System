## Read Me
#### For flawless execution of our project download all the files in one folder in your device. And just follow the steps.
>Before running our project you should confirm some software and libraries installation on your device.

For that press `win + r` and type `cmd`. And check python version.
```
python -V
```
If python not installed then install python using this [link](https://www.python.org/downloads/).
### STEP 1
We will start by opening `cmd` and directing to folder where our dataset and model is. And type `jupyter notebook` to open notebook (assuming notebook is installed on your system) on your browser.<br/>

Then open our `IOT.ipynb` file. <br/> \
You should see something like this. \
![screenshot](https://github.com/rahulagg26/Accident-Detection-and-Alerting-System-/blob/main/1.PNG?raw=true)
### STEP 2
Install the libraries you see in the screenshot using:
```
!pip install [lib_name]
```
Create a cell before the import libraries cell and run it.

Next thing is to put the directory for `train`, `test`and `val` folders.

After that you are training your dataset on our model. ***MLP Classifier*** which is 5 layered CNN model.

You have to save your model using `model.save('model_name'.h5)`.

And make a csv file and it `car_names` in the same directory.
### STEP 3
Next is to open `final.ipynb`. And install the new libraries using the syntax discussed above.

Before running the cells make sure to 
1. Connect a Webcam (if any) or else you can also use your laptop camera.
2. Login to WhatsApp web.
3. `car_names.csv` file is not open.

Run all the cells.

Use the camera to detect the accident and QR code placed on the car. 

Something like this:\
![Predict](https://github.com/rahulagg26/Accident-Detection-and-Alerting-System-/blob/44b5e4219a15238698b9bb34ec148f9beec95f41/8.jpg?raw=true)

### STEP 4

You should see a message at the end of execution of file something like
>In 148 Seconds WhatsApp will open and after 15 Seconds Message will be Delivered!

Which means you successfully ran the project.

## Thank You

If you face any problem or regarding dataset feel free to reach me at [rahulaggarwal1926@gmail.com](rahulaggarwal1926@gmail.com)
