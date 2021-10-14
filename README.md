# counterfeit_gold_detection

Please cite below paper if you use the counterfeit_gold_detection dataset.

Can Y. S. Segmentation and Classification of Original and Counterfeit Gold Images by Using Deep Convolutional Networks. Turkish Journal of Electrical Engineering and Computer Sciences (in review).

    Description of the Dataset
    Sound Classification

In this study, I used the same sized bare gold and bare copper.  I tried to reveal the difference between bare original gold and bare copper.  The proposed method tries to discriminate the sound of impact after a free fall from a specific height (15 centimeters).  I tested our methods on bare gold and bare copper.  I recorded the impact sound by using a Samsung Galaxy S5 mobile phone.  There was not any specific noise when I recorded the signals.  I experimented with free fall ten times for gold and ten times for copper from 15 centimeters height. The sounds could be accessed in the plain_sound folder.

    Image Classification

With  the  Nikon  D90  camera,  I  experimented  differentiation  of  gold  and  copper  from  high-resolution  image processing.  I recorded an equal number of high-resolution pictures from bare counterfeit and original gold.  30 bare gold and 30 bare copper pictures were taken.  Distance to the camera lens, angle and amount of light was equal for each case. The more difficult task is to classify gold and copper inside mika.  Mika can reflect or absorb light which makes  it  more  challenging  to  discriminate  the  color  of  original  gold  from  counterfeit  gold.   I  took  pictures from sunlight, fluorescent light and dim light environments.  High accuracies could not be obtained from direct sunlight and direct fluorescent light environments because mika reflects light and shines [1].  In the dim light, I experimented on 30 gold in mika and 30 copper in mika pictures.

    Image Segmentation 

To use a CNN-based segmentation toolbox (dhSegment [2]) to detect metal parts in the image,  I formed a dataset with annotations that belong to two different object classes.  The background is the first class, which is the area between the metal and image borders.  It is marked in black color.  The second class is the metal fields, and I colored them red.  I marked 60 images (30 copper inside mika and 30 gold inside mika) with the described annotations. Image and sound data are divided into 80% training and 20% test partitions. It has original images and annotated label files for both training and test partitions.  It could be used to classify both sound and images and segment metal inside images.

[1] Can, Y. S., Alagöz, F., Özer, E., & Gündebahar, M. (2015, May). Counterfeit gold identification using sound and image processing. In: 2015 23nd Signal Processing and Communications Applications Conference (SIU); Malatya, Turkey; May 16-19, 2015. pp. 1074-1077.

[2] Oliveira, S. A., Seguin, B., & Kaplan, F. (2018, August). dhSegment: A generic deep-learning approach for document segmentation. In 2018 16th International Conference on Frontiers in Handwriting Recognition (ICFHR); Niagara Falls, NY, USA; 2018; pp. 7-12.
