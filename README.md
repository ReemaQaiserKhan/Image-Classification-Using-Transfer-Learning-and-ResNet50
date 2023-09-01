# Image-Classification-Using-Transfer-Learning-and-ResNet50
Readme: <\br>
Do this when you've once created a model, saved it, zipped it, and downloaded it to your system. </br>
Now we want to use the already saved model.
1- First upload workspace.zip in colab, unzip it.
2- Execute the code: model = tf.keras.models.load_model('/content/workspace/saved_model/my_model') model.summary()
3- Reload Cell # python librairies installation
4- Reload Cell # display, transform, read, split ...
5- Reload Cell # define classes name
6- Upload an image in Colab
7- Execute Code: #test the new image (Give path of the image uploaded in Colab)
8- Execute Code: # generate predictions for samples
9- Execute Code: # generate argmax for predictions
10- Execute Code: # transform classes number into classes name

Image Classification using Transfer Learning and ResNet50.ipynb is the jupyter notebook.

data.zip consists of 5 flower classes.
class_names = ['daisy','dandelion','roses','sunflowers','tulips']

workspace.zip is the saved model.
