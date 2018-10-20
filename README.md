# RoadDamageGAN

## Abstract
Many studies have used machine learning and image processing to automatically detect road damage.
However, as serious road damages (pot hole, etc.) are less frequent, collecting sufficient amount of training data and adequately training the damage detection model are difficult.
Therefore, in this study, we showed that by using generative adversarial networks (GANs) to obtain a damaged road image and use it as training data, the accuracy of judging the damage detection model can be improved. We conducted experiments using 15,430 damaged road images, and showed that the use of GAN-generated images improves the accuracy of judgment from 92% to 94%. We also showed the differences in the accuracy of the classification model based on the number of original training data. The dataset, our experimental results, and the code used in this study are publicly available.

## Figures

<img alt="img0" src="https://github.com/sekilab/RoadDamageGAN/sampleImages.pdf" width="400px"/>
Left: Sample image of Road Damage Dataset~\cite{c9}, middle: cropped area from the original image, right: resized image of \(128\times128 pixels\) from the cropped image


<img alt="img1" src="./sampleImages.pdf" width="400px"/>
From top raw to bottom, original damaged-road images, and generated images trained by 100, 500, 1000, 5000, and 10,000 damaged-road images

<img alt="img2" src="./plotAccuracy.pdf" width="400px"/>
Accuracy results for road-damage classification with the increase of the training set. The red and blue lines show the effects of adding classic and synthetic data augmentation.

## Citation


