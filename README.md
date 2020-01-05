# chatbot_pyTorch
Developing a deep learning model using the pytorch library.

In this tutorial, we explore a fun and interesting use-case of recurrent sequence-to-sequence models. 
We will train a simple chatbot using movie scripts from the Cornell Movie-Dialogs Corpus.
https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html

> hello?
Bot: hello .
> where am I?
Bot: you re in a hospital .
> who are you?
Bot: i m a lawyer .
> how are you doing?
Bot: i m fine .
> are you my friend?
Bot: no .
> you're under arrest
Bot: i m trying to help you !
> i'm just kidding
Bot: i m sorry .
> where are you from?
Bot: san francisco .
> it's time for me to leave
Bot: i know .
> goodbye
Bot: goodbye .


# Tutorial Highlights
Handle loading and preprocessing of Cornell Movie-Dialogs Corpus dataset

Implement a sequence-to-sequence model with Luong attention mechanism(s)

Jointly train encoder and decoder models using mini-batches

Implement greedy-search decoding module

Interact with trained chatbot

# Note
When you close and turn colab on after the model's training, you'll have to retrain the model.
To resolve this, we need to save and load.
If you cannot save and load, you should download 4000_checkpoint.tar.
