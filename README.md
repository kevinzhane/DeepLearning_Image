# DeepLearning_Image
This folder is practice Deep Learning by tensorflow


## Target
Build the model for auto recognize from webcam

1. Build the webam dataset (define which item need to learning)
2. Preprocessing the input image (To cut the special contour from background)
3. Bulid different model  
   A. Teacher model (Use internet to learn associate between special image and it's meaning, then make a dataset)  
   B. Student model (Learning from Teacher model and desing & train the model for special item)  
   C. Decision model (Deside which item need to learn or not)  
   D. Enhance model (Choose the best training result of student model)  
   E. Memory model (Save all result with identified item)  
   F. Brain model (Combine above model and show the result)  
4. Show the result on webcam (when it detect the item)  


## Deep Learning Project step
1. Defined the problem and how to slove 
2. Prepare and clean the dataset
3. Bulid the dataset for model input
4. Define the solution function
5. Define the criterion of solution function (like score or accuracy)
6. Training and find the best solution function
7. Predict data use the trained model

## Tensorflow tool
1. tf.keras
2. tf.data
3. TensorBoard


