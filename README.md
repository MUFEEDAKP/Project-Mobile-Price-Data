# Project-Mobile-Price-Data

#### Dataset :
- Mobile Price Data

#### Dataset Details
1.battery_power- phone battery capacity is the amount of electricity that a fully charged battery can deliver to a stand-alone device before it is completely discharged. Simply put, this indicator can give a rough idea of how long the phone will work on its own before it is completely discharged.

2.blue - the presence of bluetooth.Bluetooth is a short-range wireless technology standard that is used to exchange data between fixed and mobile devices over short distances using UHF radio waves in the ISM bands from 2.402 to 2.48 GHz and build personal area networks (PANs). It is mainly used as an alternative to wired connections, to share files between nearby portable devices, and to connect mobile phones and music.

3.clock_speed-speed at which microprocessor executes instructions.Clock speed is the number of operations that the processor performs per second. The higher it is, the more processor performance. The number of processor cores and cache size are also important. Now even the cheapest dual-core processors come with a frequency of 3.5 GHz - this is the level of a multimedia or gaming computer of the middle class. If this indicator is higher, the possibility of overclocking the processor and the number of cores also increase.

4.dual_sim-has dual sim support or not.The term Dual Sim in a phone or smartphone means support for two SIM cards, one of which you can use, for example, for personal calls, and the second for work. Many modern smartphones support two SIM cards.

5.fc-front camera mega pixels. The front camera is a camera that looks like a small eye, which is located on the front of the phone, in the same place where the sensors are installed (that is, at the top). Other manufacturers did not pay due attention to the characteristics of the front camera in the smartphone, as they hardly interested people. The front camera was used exclusively for making video calls.

6.four_g-has 4G or not. 4G is a generation of mobile communications with increased requirements. It is customary to refer to the fourth generation as promising technologies that allow data transmission at a speed of up to 100 Mbps to mobile (with high mobility) and up to 1 Gbps to fixed subscribers (with low mobility).

7.int_memory-Internal Memory in Gigabytes. Internal Storage is a data storage on a smartphone where important data is found: the operating system (OS), installed applications, photos, videos, documents and other files.

8.m_dep-mobile Depth in cm.

9.mobile_wt-Weight of mobile phone.

10.n_cores-Number of cores of processor.The total number of cores in a single processor in an Android smartphone is typically eight (most iPhone upgrades have six). "The number of nuclear strikes on smartphone performance." big.LITTLE, in turn, stands for simply: there are cores that are more productive (large) and less productive (small).

11.pc-Primary Camera mega pixels. The number of megapixels of a camera sensor describes the image resolution that can be captured with this camera. For example, cameras with a 12 megapixel sensor can take photos with a resolution of 4200x2800 pixels, an 8 megapixel camera allows you to take pictures with a resolution of 3264x2468 pixels.

12.px_height-Pixel Resolution Height.

13.px_width-Pixel Resolution Width.

14.ram-Random Access Memory in Megabytes.Random Access Memory (RAM) is the link between the processor and the playback system because it contains temporary information necessary for running applications to run.

15.sc_h-Screen Height of mobile in cm.

16.sc_w-Screen Width of mobile in cm.

17.talk_time-longest time that a single battery charge.

18.three_g-has 3G or not.Mobile communication of the third generation is built on the basis of packet data transmission. Networks of the third generation 3G operate on the border of decimeter and connected to the network. They allow you to organize videotelephony, watch movies and individual content on your mobile phone.

19.touch_screen-has touchscreen or not. A touchscreen, in fact, is a touch glass that works according to a simple scheme: touching the observer allows you to realize any functions or symptoms of exposure.

20.wifi-has wifi or not. Wi-Fi is a wireless networking technology that allows devices such as computers (laptops and desktops), mobile devices (smartphones and wearables), and other equipment (printers and camcorders) to access the Internet.

21.price_range This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

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
- KNN
- Decision Tree
- Random Forest
- XGBoost




### Comparison of all Models:

| Model | Accuracy Percentage | 
| --- | --- |
| Logistic Regression | 65% |
| RandomForestClassifier | 80% |
| DecisionTreeClassifier | 79% |
| KNN | 82% |
| XGB | 83% |

## Conclusion:


###### XGBoost Classifier is best amoung the model with an accuracy score of 83%

