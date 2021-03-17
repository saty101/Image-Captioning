# Image-Captioning

Implementation of of the paper Show-Atten-Tell and use of beam search.

Bleu score of 22 with beam size of 3.

## Dataset

[Flickr8k dataset](http://nlp.cs.illinois.edu/HockenmaierGroup/Framing_Image_Description/KCCA.html), 8000 images 64x64 pixels.

## Training

Execute training:
`python train.py`
You can choose to use pre-trained embedding.

### Monitor/Track training
Change the `WANDB_TRACK = False` to `WANDB_TRACK = True`

## Notebooks
The full training and evaluation of metrics is shown in this [notebook](https://github.com/saty101/Image-Captioning/blob/main/notebooks/full_notebook.ipynb)
