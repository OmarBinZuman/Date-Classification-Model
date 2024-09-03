# Date-Classification-Model

This project focuses on the classification of dates into one of nine distinct types. Dates are a popular fruit with many varieties that often appear visually similar, making accurate classification challenging. The goal of this model is to provide an efficient solution for distinguishing between these types using machine learning techniques 



The dataset consists of images from nine different types of dates, with each type containing around 100 to 200 images. All the images were captured from the same angle against a white background in a bright area. While this ensures consistency, it also introduces the risk of overfitting, as the model may learn to rely on these specific conditions rather than generalizing to different environments or perspectives. To mitigate this, we applied data augmentation techniques such as adjusting brightness, rotating, and flipping the images to enhance the model's ability to generalize.





We chose Convolutional Neural Networks (CNN) due to their proven effectiveness in handling image data. Initially, we designed our own architecture, but this yielded a model with an accuracy of around 85%, which we found to be somewhat average.

To improve performance, we turned to a pre-trained model, specifically one based on ImageNet, and fine-tuned it on our dataset. This approach significantly boosted our results, achieving an accuracy of 94% and an F1 score of 94%.



NOTE: I CANNOT SHARE THE Dataset
