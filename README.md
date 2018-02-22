# Dataset-for-WSN-fault-detection
This labelled wireless sensor network dataset consists of a set of sensor measurements where we have injected 
different types of faults. It contain 281280 observations (Vectors). 
Each vector contain 12 attributes. 
- Original dataset: Our labelled dataset used in this work is based on an existing dataset published in 2010 by researchers at 
The University of North Carolina at Greensboro [1]. 
By the use of TelosB motes, these researchers collect the data from a simple single-hop and a multi-hop wireless sensor network. 
It consists of humidity and temperature measurements measured every 5 seconds during 6 hours. 
For this original dataset, the researchers have introduced an event on the network to collect different measures. 
They have introduced a steam from hot water to increase the humidity and temperature and then they have considered 
two classes: the normal data class and the class of anomalies. 
- Prepared dataset: For our dataset we have used only the outdoor data collected from multi-hop wireless sensor network. 
It composed by a set of observations with dimension 12. Each one (vector) contain measurements in 3 successive instances (t0, t1, t2). 
For each instance we consider 2 temperature measurements and 2 humidity measurements (T1 T2 and H1 H2). 
So, we have prepared 4688 observations (data example or vector). Then, randomly we have introduced a set of faults. 
With different rates of faults (50%, 40%, 30%, 20, and 10%) and different type of data faults (Offset, Gain, Stuck-at and Out of bounds)
we have prepared 60 datasets with 4688 observations for each one. Different values of beta have been applied. 
Each dataset in two excel files (a file for observations and a file for label y). 
y=1 for a normal observation and y= -1 for a fault observation. This work of fault detection was published in [2]. 
This labelled dataset can be used by researchers in different fields. Such as machine learning and fault detection sensor network. 

[1] Shan Suthaharan, Mohammed Alzahrani, Sutharshan Rajasegarar, Christopher Leckie and Marimuthu Palaniswami, 
"Labelled Data Collection for Anomaly Detection in Wireless Sensor Networks", 
in Proceedings of the Sixth International Conference on Intelligent Sensors, 
Sensor Networks and Information Processing (ISSNIP 2010), Brisbane, Australia, Dec 2010. 

[2] Salah Zidi, Tarek Moulahi and Bechir Alaya "Fault detection in Wireless Sensor Networks through SVM classifier", 
IEEE sensor journal, Vol. 18, NO.1, Janvier 2018.
