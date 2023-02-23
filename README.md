# Facial Recognition / Verification with facenet

* Uses facenet pre-trained weights and model
* Images directory not supplied would need to be added
* triplet_loss.ipynb is not used in the main notebook detection code.  It's an extra file to demonstrate how to train your own weights for facial recognition or verification tasks, and implement the algorithm from its mathematical definition. Since facenet is being used theres no need for a custom loss function.


Eventually plan to put this model behind an API and host it on a dedicated Raspberry Pi.  And use a camera mounted at a motorized gate to allow automatic entry to anyone whos facial encoding matches above a threshold in the database.
