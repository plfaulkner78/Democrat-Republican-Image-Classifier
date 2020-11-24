# Democrat-Republican Image Classifier

Convolutional neural networks are powerful machine learning models that can achieve great performance classifying images. Unfortunately, when learning about CNNs most of the datasets I worked with were pretty boring, like Fashion-MNIST or CIFAR-10. So I started to ask myself what would be a fascinating image classification task for me personally.

Since we were in the midst of an election season, I started to wonder whether or not it would be possible to determine someone’s political leanings based on his or her appearance alone. To answer this question, I built an image classifier trained on images of politicians with the hope that the model would be able to determine whether someone is a Democrat or a Republican based on his or her face alone. To train this model, I used the images of every member of Congress, the 435 members of the House and the 100 senators (plus some non-voting House members).

#### [To recreate my work]:

The code creating the dataset and training the model can be found in the Jupyter notebook titled "Pretrained Xception Model".

I have not included the images I used to train the model in this repo. Instead, I have included the script I used to scrape the images from the US Congress website, which can be found in the notebook titled "Congress Image Scraping". Therefore, if you want to recreate this project and get the data, you can simply run that script. However, you must first create an empty directory called "us_congress_images" so the web scraping script can store the images in the correct location.

Finally, I wrote this web scraping script in October 2020 during the 116th Congress. Therefore, if you are viewing this project far into the future, the members of Congress (and thus the data I used to train my model) will be different. Furthermore, though unlikely, the HTML structure of the Congress website may change in the future, making my scraping script ineffective. As of this post (late November 2020), the scraping script still works perfectly with the website's structure.
