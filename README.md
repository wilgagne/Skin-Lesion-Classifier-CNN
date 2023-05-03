# Skin-Lesion-Classifier-CNN

## Project Description
In this project, I aimed to adapt the renowned Esteva et al. (2017) skin lesion classifier CNN to perform effectively on a new, smaller dataset with significant class imbalances. Esteva et al.'s approach utilized Google Inception V3 and transfer learning, achieving impressive results and setting a benchmark for skin lesion classification.

I began by implementing the original Inception V3 model, following Esteva et al.'s guidelines. However, due to the severe class imbalance in my dataset, I developed a second model that addresses this issue more effectively. The new model incorporated an over-sampler and under-sampler, sklearn class weights, classical data augmentation techniques, a dropout layer, focal loss, and the Adam optimizer.

As a result, my second model significantly outperformed the original Esteva et al. model when applied to my dataset. This improvement can be attributed to several factors, including the new model's hyperparameters being tailored to a smaller dataset with severe class imbalances, the use of a loss function specifically designed to handle class imbalances, and the incorporation of an extra dropout layer and Adam's optimizer.

This project underscores the importance of considering dataset characteristics when adapting a CNN and demonstrates the potential for achieving better results by tailoring a renowned model's training procedure to suit specific dataset requirements.

## CNN General Architecture 

![CNN](https://github.com/wilgagne/Skin-Lesion-Classifier-CNN/blob/22241ba2a86b767bd506511038cd855453218d90/images/Screen%20Shot%202023-05-02%20at%207.57.44%20PM.png)
* taken from https://cloud.google.com/tpu/docs/inception-v3-advanced

## Dataset
<img src="https://github.com/wilgagne/Skin-Lesion-Classifier-CNN/blob/96a18d01da90480d49f45cee9ef98ecf9fe94491/images/ISIC_0036049%20copy.jpg" width="200" height="200"/>
<img src="https://github.com/wilgagne/Skin-Lesion-Classifier-CNN/blob/96a18d01da90480d49f45cee9ef98ecf9fe94491/images/ISIC_0036049%20copy.jpg" width="200" height="200"/>
<img src="https://github.com/wilgagne/Skin-Lesion-Classifier-CNN/blob/96a18d01da90480d49f45cee9ef98ecf9fe94491/images/ISIC_0036049%20copy.jpg" width="200" height="200"/>
