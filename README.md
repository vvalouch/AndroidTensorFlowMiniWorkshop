# AndroidTensorFlowMiniWorkshop

1) install TF
1b) https://www.tensorflow.org/install/pip
2) TensorFlow for poets: https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0
3) get your own images: https://www.raymond.cc/blog/extract-video-frames-to-images-using-vlc-media-player/
4) retrain with your new images
5) shrink your model

5) create an app
6) brand new app -> empty activity
7) gradle.build add:
  Dependency{
   implementation 'org.tensorflow:tensorflow-android:+'
  }

  android {
    aaptOptions {
        noCompress "tflite"
        noCompress "lite"
    }
  }
8) Android manifest




#Useful link:
## How to convert video to pictures
https://www.raymond.cc/blog/extract-video-frames-to-images-using-vlc-media-player/

## Basic intro
https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0
https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2-tflite/#0

##Useful blogs
https://proandroiddev.com/re-training-the-model-with-images-using-tensorflow-7758e9eb8db5
https://github.com/tensorflow/models/blob/master/research/slim/README.md
https://github.com/tensorflow/hub/tree/master/examples/image_retraining


Models: https://github.com/tensorflow/tensorflow/blob/master/tensorflow/contrib/lite/g3doc/models.md
