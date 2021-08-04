# WATS-SMS-Model
This code is for fine tuning Text Summarization model for French Wikipedia pages
### Fine Tuning Transformer for Text Summarization

Pre-trained model = T5(Text-to-Text Transfer Transforme)

Dataset language : French

Dataset source : Wikipedia


### Preparing Environment and Importing Libraries

At this step we will be installing the necessary libraries followed by importing the libraries and modules needed to run our script. 
We will be installing:
* transformers
* wandb

Libraries imported are:
* Pandas
* Pytorch
* Pytorch Utils for Dataset and Dataloader
* Transformers
* T5 Model and Tokenizer
* wandb

Followed by that we will preapre the device for CUDA execeution. This configuration is needed if you want to leverage on onboard GPU. First we will check the GPU avaiable to us, using the nvidia command followed by defining our device.

Finally, we will be logging into the [wandb](https://www.wandb.com/) serice using the login command
