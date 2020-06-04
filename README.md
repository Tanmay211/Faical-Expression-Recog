# Faical-Expression-Recog

This is a simple Deep Learning Project to recognise one of the seven universal face expressions which are :
1. Happy
2. Sad
3. Neutral
4. Fear
5. Angry
6. Surprise
7. Disgust

To try it on your own, just clone the repo and then move into the root directory of the project and install all the dependencies by:
pip install flask tensorflow opencv-python
and other dependencies as well.

Then simply run the server by the command:
python main.py
and you can see the code running on localhost:5000

## Side note
The CNN model was trained for only 15 epochs with a quite high learning rate because of my CPU constraints. So I would recommend you to
first setup the project as above and then first run the jupyter notebook and there you will find the code to build and train the CNN model.
Just change the values for the hyperparameters as per your need and CPU constraints and that's it. Once the model is trained and saved
just run the python main.py script and visit localhost and let the app recognise your expressions. Enjoy :)
