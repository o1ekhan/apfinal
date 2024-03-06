# This is object detection model by using newest YOLO v9
By Kalibekov Alikhan, Kabdeshov Dias, Kenzhebaev Diad , group IT-2207
![image](https://github.com/o1ekhan/apfinal/assets/146668684/94f172b5-b49e-44f5-adf3-6e26c0a4f6ce)
Here you can see that v9 has better performance than v8, that is why we chose it
## How to use
1. To use our model open Jupyter or any jupyter hosted service as Google colab and open apfinal.ipynb
2. Change runtime type to GPU
3. You need to create your dataset in roboflow and get the link to set it
4. Set number of epochs if 10 is not enought for you
5. After training you get message "Results saved to run/train/exp[number]"
6. In examining section, replace exp2 with you exp[number]
7. Enjoy results
----------------------------------------------------------------------------------------------------------------
## Some thoughts and explanations
1. We tried diffent models, yolo7, yolo8, SSD, Faster r cnn, but YOLO9 seemed more comfortable to use
2. We also tried different dataset platforms like Open Images dataset V7, COCO, but roboflow again seemed more comfortable to use
3. After some failed tries we understood that structure of dataset should look like this
4. https://youtu.be/CApXoenElSE This is video how our model works, but turn off the sound, becasue there are weird sounds that I was not recording(I thought)
