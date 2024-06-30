This is the final deliverable from AIdea.

In this map you will find several files and maps, this text will run you through quickly.

In Data_target is the target data we used to calculate the averages for our classification model, if you change this file, run alta_occupancy_prediction again you will have a new estimation model.

alta_occupancy_prediction shows how we made our classification and how it is saved in the later .pkl files.

In instructions you will find a walkthrough of our two applications, interface and interface_notebook, and what you need to install in order to run them.

If you run Interface you will get the Web-based UI where you can either select a day or process an entire file in both occupancy estimation modes. After that you can download the key values in a CSV file for further research.

interface_notebook is a more barebone application that you might want to use in your IDE.

Both pkl files are essential for our model to run. They can be changed by running alta_occupancy_prediction.

model.py is the model behind both applications.

requirements.txt is needed to install all the packages you need for using the applications.