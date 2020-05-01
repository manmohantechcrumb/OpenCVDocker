# OpenCVDocker
Integrating Docker, OpenCV.js and Nginx for quick deployment of real-time facial recognition machine learning models. 
This solution could easily be extended to include any readymade machine learning model from OpenCV, Keras, Tensorflow, etc.
Also,
This is a convenient solution for the Mac Docker community who is struggling to get webcam access due to the drawbacks of the Docker hyper kit support with the help of Nginx.
This is strictly designed to acquaint the reader on the deployment aspect of machine learning with Docker and is NOT concerned with building a machine learning model for facial recognition.

Working:
Step 1: Clone the Github Repository.
Step 2: Run the following command for building docker image:
#docker build -t object-detection-image .
Step 3: Start the Docker Container:
#docker-compose up
Step 4: Visit localhost:80 on your browser.
Step 5: Click the download model button. Once the model is downloaded you can add as many people as you like for the recognition.



Note:
The CV folder resides the source code for the project inclusive of the nightly build of OpenCV.js. I have used the facial recognition code from the tutorials of OpenCV.js official site(https://docs.opencv.org/3.4/d9/df8/tutorial_root.html), it is available from the official GitHub repo of OpenCV as well. The tutorials they provide is really helpful and is where I learned most of the OpenCV.js applications.
