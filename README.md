# pokemon_card_app
The goal of this is to build an application that identifies if a Pokemon card is real or fake.

The goal of this module is to help distiguish between real and counterfeit Pokemon cards. Pokemon cards have become increasingly popular over the past few years, and with that the number of counterfeit cards has also increased. Even Walmart was recently in the news for selling fake Pokemon cards. With a large number of counterfeit cards being out in the world and with a large number of buyers, it can be very easy for a potential buyer to get ripped off. The goal of this module is to help any potential buyer to avoid buying counterfeit cards and wasting their money.

The original image dataset is located here: https://www.kaggle.com/datasets/ongshujian/real-and-fake-pokemon-cards

The image format is extremely similar for all Pokemon cards in the dataset. The same camera, the same angle, the same background, and the same lighting was used for all images. This may seem like a good thing, but if a model is trained only on these images, it may not know how to interpret images taken in a different environment. Image augmentation will be completed below to emulate pictures of Pokemon cards in a different environment. The model will then include these modified images for training.

The application and model showed promise, but more work will need to be done. The app has 97% accuracy when guessing for images within the original dataset, but poor accuracy for images outside of the dataset. The model suffered from a small dataset. The dataset was also from one single source, so all images were extremely similar to one another.

For the future, the dataset itself is the area to target for improvement. I also want to include the front of cards in the model as well. I plan to revisit this project the next time I run into an image compiling project.
