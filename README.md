# SuprPixl
Superresolution with ![tensorflow.js](https://js.tensorflow.org "tensorflow.js")
 

## usage
put the files on a http server ![get one here](https://duckduckgo.com/?q=httpserver%20open%20source "get one here"), open the training.html to start the training of the model in the browser. it runs for 500 epochs and saves the model in the browser local storage. after that (or running for more epochs), click the download button to save the weights.
open the prediction.html to upload the previously downloaded model files and upscale your own image.

## references & notes
- subpixel convolution / pixelshuffle [[paper]](https://arxiv.org/abs/1609.05158)
