# MSLID
Multiple Spoken Language Identification using Deep Learning
# Introduction
In this experiment we have developed a system for identifying the name of the language speaken by a speaker.We have used CNN for identifying the language.For training purpose we are taking audio files in wav format and changing them to melspectograms.We are using torchaudio library.

![](https://github.com/Lakshman511/MSLID/blob/master/Images/WhatsApp%20Image%202020-09-14%20at%208.59.41%20PM.jpeg)

Above figure is melspectogram of a bengali audio file.
  In yraining process we are applying some augmentations to data like frequency masking and time masking.After applying those augmentations the above spectogram will look like
  
![](https://github.com/Lakshman511/MSLID/blob/master/Images/WhatsApp%20Image%202020-09-14%20at%208.59.53%20PM.jpeg)

We are using a CNN.The architecture of the network is as follows.

![](https://github.com/Lakshman511/MSLID/blob/master/Images/Network%20architecture%20(2).jpg)

The detailed diagram of above CONVBLOCK os as follows:

![](https://github.com/Lakshman511/MSLID/blob/master/Images/ConvBlockDetailed%20(2).jpg)

Below diagram illustrates the working of our model

![](https://github.com/Lakshman511/MSLID/blob/master/Images/networkWorking%20(2).jpg)

We have achieved an validation accuracy of 88.82% in best case and 96% training accuracy.
