1.There are two folders in the current directory, one with the name OpenSA, and the other with the name Transformer. these two folders are the training codes for the two classification models. We will introduce the composition of the code in these two folders in turn.

2.We have placed the data prepared in the experiment in the Data/Cls/ folder, which is a file named 1.csv. This file is the collected soil XRF dataset, one row of this dataset represents the spectrum of a sample, and finally the moisture content of the soil is represented by the numbers 0, 1,2,3. 0, 1, 2 and 3 represent the moisture content of the soil as 0%, 10%, 20% and 30%, respectively. Similarly, there is a Data folder inside the Transformer folder. It contains the dataset from the experiment. In Transformer this dataset is named table.csv and it is the same as the dataset in OpenSA.

3.Firstly the first one is the OpenSA folder, within this folder there are some folders for the regression task and the classical models for the classification task are concentrated in the folder named Classification. In this folder are included the classic classification models CNN, RF, SVM. the CNN.py file contains the code for CNN model training, and the other concentration of classic neural network models, all stored in the ClassicCls.py file.

4.If you need to run the code, you can run the example.py file directly. However, for scholars who are using this file library for the first time, the probability is that a reminder of the missing necessary software libraries will appear. You need to follow the prompts to install all the necessary libraries. Subsequently, you can see the training process printed out under the terminal interface. It is worth noting that if you want to run your own dataset, you need to change the file path of the Dataload.py code in the Dataload folder and check that the data is structured correctly.

5.For the transformer model it is even easier to use, you can start training the model by running the TableVitRun.py file directly from the folder. Again, if you get warnings and errors about missing libraries, you will need to install the appropriate libraries first.

6.We have provided the origin files for this experiment in the origin folder, which contains not only the images themselves, but also the tables. The tables store all the data sets relevant to this experiment. These datasets can be used for secondary purposes or as a reference for future research.
