# Fine-Tuning

Sometimes, it does not make sense to train a model from scratch. Instead, we can take a base model and train it a little bit more on a custom dataset so that it completes the task at hand. This is known as fine-tuning, and it is especially useful when we have a relatively small dataset.

The dataset for this lesson contains MRI scans of 3 different brain conditions, with almost 500 samples each (the [original dataset](https://www.kaggle.com/datasets/orvile/brain-cancer-mri-dataset?resource=download) had 2000 each, but it was cut down to reduce the time it takes). Instead of training a CNN from scratch, we will fine-tune a few different architectures and compare them.