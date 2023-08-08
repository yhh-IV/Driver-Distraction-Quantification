# Driver-Distraction-Quantification

We develop a supervised contrastive learning framework to recognize the distracted driving, in which the driver distraction behaviors can be quantified using their distances from normal ones in the latent space. Note that the dataset can be downloaded from the [SAM-DD website](https://yanghh.io/SAM-DD/).

![illustration](https://github.com/yhh-IV/Driver-Distraction-Quantification/blob/main/images/illustration.jpg)

* **Visual examples**

&emsp; &emsp; &emsp; &emsp; &emsp; normal driving   &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; making hair 

<img src="https://github.com/yhh-IV/Driver-Distraction-Quantification/blob/main/images/normal-driving.gif" width="300" alt=""> <img src="https://github.com/yhh-IV/Driver-Distraction-Quantification/blob/main/images/making-hair.gif" width="300" alt="">

&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; phoning   &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &nbsp; texting 

<img src="https://github.com/yhh-IV/Driver-Distraction-Quantification/blob/main/images/phoning.gif" width="300" alt=""> <img src="https://github.com/yhh-IV/Driver-Distraction-Quantification/blob/main/images/texting.gif" width="300" alt="">

* **Supplementary experimental results**

The recognition accuracy of different backbones under our proposed W-SupCon learning paradigm. 

| Models | AUC-v1 | 3MDAD (day) | DAD | SAM-DD |
| :---: | :---: | :---: | :---: | :---: |
| ShuffleNet-v2 | 0.9431 | 0.9354 | 0.8870 | 0.9548 |
| MobileNet-v3 | 0.9491 | 0.9348 | 0.8944 | 0.9470 |
| ResNet-18 | 0.9547 | 0.9362 | 0.8949 | 0.9583 |
| VGG-16 | 0.9611 | 0.9370 | 0.8968 | 0.9678 |
| Vision Transformer | 0.9651 | 0.9375 | 0.9010 | 0.9701 |
| Swin-T | 0.9702 | 0.9440 | 0.9091 | 0.9725 |

				










