
Requirements
`Hardwares:`
1. RaspberryPi 2 with Picamera                                                                                               
2. Mouse And Keyboard                                                                                                        
3. Monitor                                                                                                                   
`Software:`                                                                                                                  
1. Raspbian OS Jessie                                                                                                        
2. OpenCV 2.4.10                                                                                                             
3. Python 2.7                                                                                                                
4. Sendgrid API key                                                                                                          
5. Microsoft Azure Emotion API key                                                                                           
6.  Python Libraries:                                                                                                        
    -cv2                                                                                                                     
    -dlib                                                                                                                    
    -numpy                                                                                                                   
    -skimage                                                                                                                 
    -skicit-learn                                                                                                             
    -imutlis                                                                                                                 
    -pymongo                                                                                                                 
    -pyimgur                                                                                                                 
    -sendgrid                                                                                                                
    



















1.First we run the code to detect faces and store ID , name , age , email address                                               
  this will capture 10 images per face of the user and store it into dataset
  ```
    $ sudo python detect.py --picamera 1   
  ```
   
2.Next we will train our dataset using following command   
```
  $ sudo python train.py              
  ```
                                                                                                                               
3.Now we will run recognition code to recognize faces using following command             
```
  $ sudo python testrecog.py --picamera 1                                                                                       
```
