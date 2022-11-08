# Recognising legal characteristics of the judgments of the European Court of Justice: Difficult but not impossible
## Short paper released for [JURIX 2022, conference on Legal Knowledge and Information Systems.](https://jurix2022.rechtsinformatik.saarland/accepted-papers/#:~:text=Recognising%20legal%20characteristics%20of%20the%20judgments%20of%20the%20European%20Court%20of%20Justice%3A%20Difficult%20but%20not%20impossible%0AAlessandro%20Contini%2C%20Sebastiano%20Piccolo%2C%20Lucia%20Lopez%20Zurita%20and%20Urska%20Sadl)




Machine learning has improved significantly during the past decades, with computers performing remarkably in formerly difficult tasks. This article reports the preliminary results on the prediction of two legally relevant characteristics of judgments of the European Court of Justice, doctrinal outcome and deference. The variables require the knowledge of concepts and doctrines of European Union law and judicial decision-making. The analysis relies on 1704 manually labelled judgments and trains a set of classifiers based on word embedding, LSTM, and convolutional neural networks. The preliminary findings suggest that all classifiers exceed simple baselines, learning meaningful representations of the judgments. Yet, the overall performance is rather weak, suggesting that the usual limitations of machine learning, including small training data, significant class imbalance and the characteristics of the variables requiring external knowledge pose a significant challenge to machines learning the law.
The article also outlines directions for future research.

Please refer to our working paper [here](https://github.com/Contedigital/Classification-of-legal-labels-JURIX-2022/blob/main/Classification_of_legal_labels_Working_Paper-3.pdf) for further and detailed explantions about the approach and the results.

Authors: Alessandro Contini, Sebastiano Piccolo, Lucia Lopez Zurita and Urska Sadl

December 2022


NOTE: the code in this repository is an example of the final neural networks used for the predictions. 
Please, contact one of the authors for the full code containing datasets, algorithms for paramaeter tuning and the final models.
