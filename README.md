# Advanced Topics in Artificial Intelligence - final project

Our visual system and brain work together in order to identify and recognize images and objects with a very high speed and accuracy, as long as they are not impaired. A very good source forvisual perception from a clinical viewpoint is Schwartz’s book. A 2-year old child needs to seeand be introduced to a small number of images and explanations in order to distinguish, say, acat from a dog or any other animal, even if the image is blurred or the object is partially blocked.The state-of-the-art computational model to recognize images is based on neural networks, inparticular, deep neural networks composed by a number of layers. 

In contrast to the human recognition model, deep neural network models require a large number of training instances inorder to distinguish a cat from a dog, and if the images are noisy, they lose their predictive power.In this assignment you will be practicing with neural networks that distinguish among animal sand will add more methods trying to improve the model. 

**The main objective is to understand why deep learning alone may not be a good learning model and explain how we could achieve agood computational human-like model** (achieving the holy grail?). Below you can find a list of your tasks.

1. Go to the tutorial found [here](https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-photos-of-dogs-and-cats/) and repeat the whole process.
2. Create new images containing noise (for example, Gaussian white noise) or mask theimages placing some blocking artifact.
3. Repeat the tutorial with these new images added to the original ones: have the results improved or got worse?
4. Train your models with networks different from VGG (for example, resnet, rexnet or similar).
5. Add a new class of animals, for example, pandas (you can create new images using in-structions on [this site](https://pyimagesearch.com/2018/04/09/how-to-quickly-build-a-deep-learning-image-dataset/)).
6. Train your models again: can you classify well when you add other classes of animals? What if the classes are imbalanced? Does it matter to the humans? Does it matter to the computational models?
7. Another way of training is using a description of the images (a very simple way of doingit is shown [here](https://medium.com/@TheGeekiestOne/how-to-teach-a-computer-to-distinguish-cats-from-dogs-d66cc0679287), but you can also fecth images and image metadata from this [kaggle competition](https://www.kaggle.com/competitions/petfinder-pawpularity-score)).
    + Train new models using the new way of describing the original images.
    + Add a new kind of animal and describe them: can the classifier improve or not?
    + Can the integration of images with annotated features improve reults?
    + Can you devise a better way of describing images/objects using any kind of knowledgerepresentation (tabular, graph-based, logic-based, ontology-based, semantic-based,probabilistic-based etc)?
    + Does a new representation produce good results?
8. Try applying reinforcement learning to this problem.  How would you represent it andwhat is the reward function?

# Solution
1. The dataset used to implement the classification of dogs and cats was collected from this [link](https://www.kaggle.com/c/dogs-vs-cats/data)
2. We added the butterfly as a new class and this type animal was chosen because it has a totally different shape than other two.
The dataset for butterflies was collected in these two places: [link 1](https://www.kaggle.com/datasets/antoreepjana/animals-detection-images-dataset) and [link 2](https://www.kaggle.com/datasets/fca804bc32fc65614ee308bd728b530e36ca3d3cbb7c770da10a975da6b8337e)
3. All the code to solve the proposed project can be found in the code folder here in the repository.
4. It is also available the presentation and the final report.
