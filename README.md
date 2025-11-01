# DetectingHoaxMultimodel

<img align="left" src="https://github.com/rizalarb/Application-Multimodel-Deep-Learning-Detecting-Hoax-News-Turnbackhoax.id-CNN/blob/master/Cover PA English.jpg"> 

### Abstract
The increasing spread of hoax news has prompted the public’s need to address this issue. The Indonesian Anti-Slander Society (Mafindo), as an independent community, strives to provide education and identification regarding hoax news. However, the manual verification process proves ineffective given the rapid and large-scale dissemination of hoax news. Therefore, research is conducted to build a machine learning model using deep learning, specifically convolutional neural network (CNN), for the fast and automatic classification of hoax news. The use of CNN based on text and image data has shown good classification performance, especially when both data types are combined in multimodal deep learning. Multimodal deep learning, or the combined CNN model, merges text-based CNN (CNN 1D) and image-based CNN (CNN 2D), demonstrating superior performance compared to a single model (unimodal). The model is then trained with 3103 training data and 775 testing data, resulting in an accuracy of 99.35% and an AUC of 99.81%. Evaluation results indicate excellent performance in classifying hoax news both within and outside the model.
#### Keywords: CNN, Hoax, Multimodal Deep Learning.


**Highlights:**
- Built a **multimodal CNN architecture** by merging text-based CNN (1D) and image-based CNN (2D).  
- Processed **textual data** using Word2Vec embeddings and **visual data** using convolutional feature extraction.  
- Trained and tested on the **Turnbackhoax.id dataset** with **3,103 training** and **775 testing samples**.  
- Achieved **99.35% accuracy** and **99.81% AUC**, outperforming unimodal baselines.  
- Provided a scalable approach for **automated hoax verification**, supporting anti-disinformation efforts by **Mafindo (Indonesian Anti-Slander Society)**.

**Tools:** `Python`, `TensorFlow`, `scikit-learn`, `Pandas`, `Matplotlib`
