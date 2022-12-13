## HYPER-VIT : A NOVEL LIGHT-WEIGHTED VISUAL TRANSFORMER-BASED SUPERVISED CLASSIFICATION FRAMEWORK FOR HYPERSPECTRAL REMOTE SENSING APPLICATIONS

### Introduction
Hyperspectral Imagery (HSI) data inherently has the ability to store finer details in the form of reflectance information through its contiguous spectral bands, which is utilized to discriminate between materials included in the data. With the emergence of deep learning (DL) over the last decade and the extent to which it has influenced applications and research in the domain of remote sensing is significant. Convolutional neural networks (CNNs), residual networks (ResNets), recurrent neural networks (RNNs), and other deep learning constructs have been employed to develop remote sensing-based computer vision applications, and have produced excellent results time and time again. However, the aforementioned deep learning constructs lack the intrinsic ability to prioritize data features based on how cardinal they are in mapping inputs to ground-truths, generally called attention, thus not exploiting the underlying architecture’s potential to the fullest. Hence, in this work, we explore the breadth of influence of a novel, computationally efficient visual transformer (ViT) based architecture on HSI data based classification tasks. The efficacy of the proposed architecture is evaluated through a series of experimentation and the performance is compared against other state-of-the-art attention based HSI data classification methodologies on two datasets, Salinas and Pavia University. When compared to other approaches discussed, experimental results show that our proposed methodology outperformed them in terms of classification efficacy and computational complexity under limited training samples scenario.

---

### Datasets

**Name :** Pavia University

**Size :** (610 x 340 x 103) pixels

#### Ground Truth (Labels)
<img src="https://user-images.githubusercontent.com/79660080/207453775-f46ce80a-ab60-41e0-9cc8-0a4028a56a33.PNG" width="300" height="250">

**Name :** Salinas Valley

**Size :** (512 x 217 x 224) pixels

#### Ground Truth (Labels)
<img src="https://user-images.githubusercontent.com/79660080/207454226-5e818e6f-901e-40fd-8b06-c2064d0186d7.PNG" width="300" height="250">

---

### Overall System Architecture
<img src="https://user-images.githubusercontent.com/79660080/207454576-9a60fda9-d532-481b-a27e-766590d388cd.PNG" width="700" height="350">

---

### Results

#### Classification Map (Pavia University) (2% Training Data - Accuracy : 97.19%)
<img src="https://user-images.githubusercontent.com/79660080/207455273-ac67c4ba-76e3-445f-9b81-8adcb3fc0532.PNG" width="130" height="250">

#### Classification Map (Salinas) (2% Training Data - Accuracy : 94.80%)
<img src="https://user-images.githubusercontent.com/79660080/207455918-e5ea836e-9050-480c-bcfc-16b56fea2f31.PNG" width="130" height="250">

---

#### Overall Classification Accuracy - Pavia University (1% - 5% Training)
<img src="https://user-images.githubusercontent.com/79660080/207456893-4fef3113-343b-496c-a4f7-6f7c4e29e675.png" width="350" height="250">

#### Overall Classification Accuracy - Salinas (1% - 5% Training)
<img src="https://user-images.githubusercontent.com/79660080/207456729-ca078584-49f3-416b-99b6-5f31913ba8f1.png" width="350" height="250">
