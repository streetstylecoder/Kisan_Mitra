
KISAN MITRA 🤝

Kisan mitra is a ML powered application which enables farmers to know more about their farms guiding them what they should really grow depending on thier location and the soil at that place
<br>
##The usecase of our website is <br>
1)Crop and suggestions advisor based on geographical location and soil<br>
2)Crop disease identification using deep learning models<br>


![image](https://user-images.githubusercontent.com/89967721/218291543-2dd6245c-d84c-4d23-929e-7ca83cd868da.png)
<br><br>
The farmers just have to enter a few details about their geographical details and the soil at that place 
![image](https://user-images.githubusercontent.com/89967721/218291562-9b0c74b9-43c0-4ac3-918a-a23bb92bc276.png)
<br>
and tada Kisan Mitra application shows the complete detailed anayslsis for that place with suggestions on which fertilizer to use

<img width="1440" alt="Screenshot 2023-02-12 at 9 06 58 AM" src="https://user-images.githubusercontent.com/89967721/218291608-1dd1394d-a1cd-472a-aa4b-e0340af738a7.png">
<br>
Moreover the application can be used to identify and list down the disease of the plant by uploading a image of it  <br><br>
It identifies the plant the disease it's going through and list it's causes and solution

![image](https://s9.gifyu.com/images/mov-1.gif)
<a href="https://gifyu.com/image/Sqlgz"><img src="https://s9.gifyu.com/images/mov-1.gif" alt="mov-1.gif" border="0" /></a>

<br><br>
#Requirements of application
1)numpy<br>
2)pandas<br>
3)Flask<br>
4)scikit-learn<br>
5)https://download.pytorch.org/whl/cpu/torch-1.7.0%2Bcpu-cp36-cp36m-linux_x86_64.whl<br>
6)https://download.pytorch.org/whl/cpu/torchvision-0.8.1%2Bcpu-cp36-cp36m-linux_x86_64.whl<br>
7)requests<br>
8)Pillow<br>
9)gunicorn == 20.0.4<br>
<br><br>
#DATA SOURCE 
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) (custom built dataset)
- [Fertilizer suggestion dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv) (custom built dataset)
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

<br><br>
How to run this project in your computer <br>
1.Dowload zip<br>
2.Extract <br>
3.install all the required dependncies <br>
4.run the command ```flask --app app run```<br>
5.The website will be live on localhost<br>

