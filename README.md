# SlobodaStudio-face-recognition


## Solution algorithm:
1. Initially we are preparing a photos database of people whom we will recognize in the future
![alt text3](https://github.com/UdovenkoVolodymyr/SlobodaStudio-face-recognition/blob/master/1.jpg)
2. When the database is ready, we connect the video stream from the webcam and use cnn to detect the faces in the photo
![alt text4](https://github.com/UdovenkoVolodymyr/SlobodaStudio-face-recognition/blob/master/2.jpg)
3. Then, with the help of another cnn, we highlight landmarks on the face
![alt text4](https://github.com/UdovenkoVolodymyr/SlobodaStudio-face-recognition/blob/master/3.jpg)
4. Then we compare them with already known templates
![alt text4](https://github.com/UdovenkoVolodymyr/SlobodaStudio-face-recognition/blob/master/4.jpg)

## Technologies that have been applied
For our project  we don't need powerful and expensive hardware, only compact raspberry pi and camera.
![alt text4](https://github.com/UdovenkoVolodymyr/SlobodaStudio-face-recognition/blob/master/5.jpg)
1. cvlib</br>                   
2. dlib</br>                    
3. face-recognition</br>       
4. Keras</br>                   
5. matplotlib</br>                  
6. numpy</br>                
7. opencv-contrib-python</br>    
8. Pillow</br>                      
9. scikit-learn</br>                
10. tensorboard</br>              
11. tensorflow</br>

## Demonstration of the algorithm, click on the image to go to the video viewing
[![Alt text](https://img.youtube.com/vi/8YST5EGInfE/0.jpg)](https://www.youtube.com/watch?v=8YST5EGInfE)
