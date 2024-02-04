# Deep Learning Based Cyclone intensity prediction

## Cyclone Intensity Estimation using Deep Learning

A user-friendly web application interface has been developed, allowing users to upload INSAT-3D IR Satellite Images of Cyclones. These images are then processed through our custom-built Deep Convolutional Neural Network implemented in PyTorch. The neural network has been meticulously trained on Cyclone imagery of various intensities using a specialized dataset created from raw INSAT-3D satellite-captured images available on the MOSDAC server.

By employing this CNN, the necessity for traditional methods to accurately determine the center of Cyclones and estimate their intensity using satellite imagery has been eliminated.

Upon processing, the model promptly provides an estimated intensity of the satellite cyclone image in knots. Additionally, users have the flexibility to upload metadata values such as datetime, latitudinal position, etc., for the cyclonic event. These values are stored in a database, creating an archive of all past cyclonic events inputted through the interface. Users can easily access and visualize the past cyclonic events in the database along with their associated metadata.

The web application is seamlessly integrated using Flask, facilitating a smooth and interactive experience for users in Python.

## Tech Stack Used

Front-end: HTML , CSS, Bootstrap and JavaScript

Back-end: PostgreSQL, Flask, psycopg2 and Python

Machine-learning-pipeline: PyTorch


## Screenshots and reference Images

``Home section:`` landing section of the website

![Screenshot (420)](https://github.com/DeepikaA2004/Deep-Learning-based-Cyclone-intensity-prediction/assets/110418508/33cc0205-5ab6-4903-bd53-5a0c1a5979d2)


``Form section:`` used to pass the image to the model which computes intensity and forwards input data to the archive via database

![Form](https://user-images.githubusercontent.com/101162842/163724953-f8479e57-267e-4560-8a1c-9761afe49f35.jpg)


``Live Weather Map:`` made using Windy API, showing live wind patterns and redirects the map to the coordinates recieved as input, incase of a cyclone, highlights the area with strong wind pattern

![Windy map](https://user-images.githubusercontent.com/101162842/163724954-7d91ff9a-be77-436a-967c-a067c485af4f.jpg)


``Archive Table:`` displaying all previously uploaded data stored in database

![Archive Table](https://user-images.githubusercontent.com/101162842/163724961-db84f65f-4d13-49dc-8d97-d30726918a14.jpg)


``Submitted Image:`` Would be displayed as

![Image image](https://user-images.githubusercontent.com/101162842/163724965-9bdb6f09-1d3f-4d4b-be08-dfd7bfdcde03.jpg)

