1.First we run the code to detect faces and store ID , name , age , email address                                               
  this will capture 10 images per face of the user and store it into dataset
  ```
   $ sudo pyhton detect.py --picamera 1   
  ```
   
2.Next we will train our dataset using following command   
```
  $ sudo python train.py              
  ```
                                                                                                                               
3.Now we will recognition code to recognize faces using following command             
```
  $ sudo python testrecog.py --picamera 1                                                                                       
```
