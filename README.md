# Project-Mobile-Price-Data

#### Dataset :
- [Mobile Price Data](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)

#### Dataset Details
- Battery_power- phone battery capacity is the amount of electricity that a fully charged battery can deliver to a stand-alone device before it is completely discharged. Simply put, this indicator can give a rough idea of how long the phone will work on its own before it is completely discharged.

- Blue - the presence of bluetooth.Bluetooth is a short-range wireless technology standard that is used to exchange data between fixed and mobile devices over short distances using UHF radio waves in the ISM bands from 2.402 to 2.48 GHz and build personal area networks (PANs)

- Clock_speed-speed at which microprocessor executes instructions.Clock speed is the number of operations that the processor performs per second. The higher it is, the more processor performance. 

- dual_sim-has dual sim support or not.The term Dual Sim in a phone or smartphone means support for two SIM cards, one of which you can use, for example, for personal calls, and the second for work. Many modern smartphones support two SIM cards.

- Fc-front camera mega pixels. The front camera is a camera that looks like a small eye, which is located on the front of the phone, in the same place where the sensors are installed (that is, at the top). Other manufacturers did not pay due attention to the characteristics of the front camera in the smartphone, as they hardly interested people. 
- Four_g-has 4G or not. 4G is a generation of mobile communications with increased requirements. 

- Int_memory-Internal Memory in Gigabytes. Internal Storage is a data storage on a smartphone where important data is found: the operating system (OS), installed       applications, photos, videos, documents and other files.

- M_dep-mobile Depth in cm.

- mobile_wt-Weight of mobile phone.

- n_cores-Number of cores of processor.The total number of cores in a single processor in an Android smartphone is typically eight (most iPhone upgrades have six). 

- pc-Primary Camera mega pixels. The number of megapixels of a camera sensor describes the image resolution that can be captured with this camera. 

- px_height-Pixel Resolution Height.

- px_width-Pixel Resolution Width.

- ram-Random Access Memory in Megabytes.Random Access Memory (RAM) is the link between the processor and the playback system because it contains temporary information    necessary for running applications to run.

- sc_h-Screen Height of mobile in cm.

- Sc_w-Screen Width of mobile in cm.

- Talk_time-longest time that a single battery charge.

- Three_g-has 3G or not.Mobile communication of the third generation is built on the basis of packet data transmission. 
- Touch_screen-has touchscreen or not. A touchscreen, in fact, is a touch glass that works according to a simple scheme: touching the observer allows you to realize any functions or symptoms of exposure.

- Wifi-has wifi or not. Wi-Fi is a wireless networking technology that allows devices such as computers (laptops and desktops), mobile devices (smartphones and wearables), and other equipment (printers and camcorders) to access the Internet.

- Price_range This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

### Problem Statement:

####   Build a model to  perform the task of Mobile Prediction with Machine Learning using Python
### Implementation:
##### Libraries: - NumPy
- pandas 
- sklearn
- Matplotlib 
- Seaborn
- Sklearn
###  Structure:
- Part 1 : Importing Libraries
- Part 2 : Reading and Preparing the dataset
- Part 3 : Exploring the data
- Part 4 : Cleaning the data
- Part 5 : Extracting the data
- Part 6 : Visualizing the data
- Part 7 : Creating a model
- Part 8 : Conclusion

### Applying some machine learning models:
 Here our aim is to create a model to predict the price of mobile. Here, the models used are:

- Logistic Regression 
- Random Forest
- KNN
- SVM




### Comparison of all Models:

 | Model | Accuracy Percentage | 
| --- | --- |
| Logistic Regression | 0.65 |
| RandomForestClassifier | 1.0 |
| SVM | 0.95 |
| KNN | 0.93 |

## Conclusion:


###### Randomforest Classifier is best amoung the model with an accuracy score of 1.0%

