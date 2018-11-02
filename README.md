# Virtual Mouse Using Gesture Recognition
Implementing a virtual mouse using gesture recognition . 

#### Required Modules :
  - Opencv   
    ```bash
      pip install opencv-python
    ```
  - Numpy 
    ```bash
      pip install numpy
    ```
  - Pynput  
    ```bash
      pip install pynput
    ```
  - WX
    ```bash
      pip install wxpython
    ```

#### How it works ?

Generally moving a mouse has two states :
  - Moving the Cursor 
  - Clicking

Now we consider that we'll be detecting two objects (green color), and if the both appear this is the first state(moving the cursor) and if they are too near so that they form one single detected object this considered as the second state(clicking mode)

Finally ,this is how it will look like. 

#### Moving the Cursor :
    
   ![alt text](https://github.com/moadmmh/Virtual-Mouse-Using-Gesture-Recognition/blob/master/cursor.jpg)

#### Clicking :
   
   ![alt text](https://github.com/moadmmh/Virtual-Mouse-Using-Gesture-Recognition/blob/master/clicking.jpg)
