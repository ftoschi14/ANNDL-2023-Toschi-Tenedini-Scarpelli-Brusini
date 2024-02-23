# Artificial Neural Networks and Deep Learning - AY 2023/2024

 Team: [Drip Mac](http://chrome.ws.dei.polimi.it/images/thumb/d/d8/ThePoint.jpg/350px-ThePoint.jpg)

 The challenges for the course "Artificial Neural Networks and Deep Learning" for the AY 2023/2024 were centered on:
 1. Image Classification
 2. Time Series Forecasting

 In both challenges, our team was awarded the maximum grade of **5.5/5**

## Challenge 1: Image Classification
<p align="center">
	<img src="images/plants.png" height="250" />
</p>

In this challenge, the goal was to train a classifier to correctly predict whether an image represented a **healthy** or **unhealthy** plant.
Our focus was on three different paradigms:
- Custom CNNs
- Transfer Learning + Fine Tuning of Pre-trained models
- Self-Supervised Learning and Ensemble models

All of which yielded notable results, specifically **Transfer Learning** + **Fine-Tuning** turned out to be the best formula for this type of problem.

Moreover, because the provided dataset only consisted of 5004 images, **Data augmentation** was a critical part of this challenge. For this reason, we developed a custom augmentation pipeline which included:
 - Random Flips
 - Random Translations
 - Random Rotations
 - Random Zoom
 - Random Brightness
 - Random Crop
 - Custom Random Perspective Skew

 Additional care was given to finding the best parameters, to prevent augmentations from **cutting-out** pixels that contained valuable information for the classification task.

 For a more in-depth overview of the challenge, please refer to the **report** and the **notebooks**.

 ## Challenge 2: Time Series Forecasting
<p align="center">
	<img src="images/plants.png" height="250" />
</p>

 For a more in-depth overview of the challenge, please refer to the **report** and the **notebooks**.

 ## Team Members
 Leonardo Brusini
 <p>
 Marco Scarpelli
<p>
 Davide Tenedini
<p>
 Federico Toschi
