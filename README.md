# Deep-Dream-Pytorch

- Clean and lucid implementation of Deep Drream algorthm in pytorch


## Introduction

DeepDream is a computer vision program created by Google engineer Alexander Mordvintsev that uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia, thus creating a dream-like appearance reminiscent of a psychedelic experience in the deliberately over-processed images.Google's program popularized the term (deep) "dreaming" to refer to the generation of images that produce desired activations in a trained deep network, and the term now refers to a collection of related approaches.

## Usage
    gh repo clone unboxdisease/Deep-Dream-pytorch
    cd Deep-Dream-pytorch
    jupyter notebook

### Screenshots
![image](https://user-images.githubusercontent.com/56218470/175814088-efb1b9bb-1b55-4554-acc6-48249ab1d0f5.png)
![image](https://user-images.githubusercontent.com/56218470/175814111-d038b47e-ccbc-40ae-b1bc-cf745d1f1873.png)




### Content
- we simply feed the classification network an arbitrary image or photo and let the network analyze
the picture. We then pick a layer and ask the network to iteratively enhance whatever it detected.
Each layer of the network deals with features at a different level of abstraction, so the complexity of
features we generate depends on which layer we choose to enhance.[1]
- The image is then modified to increase these activations, enhancing the patterns seen by the
network, and resulting in a dream-like image.
- The cited resemblance of the imagery to LSD- and psilocybin-
induced hallucinations is suggestive of a functional
resemblance between artificial neural networks and
particular layers of the visual cortex. [2]

### Requirements

    Pytorch
    Opencv-python
    Jupyter Notebook




### Reference
[1] MORDVINTSEV, ALEXANDER; OLAH, CHRISTOPHER; TYKA, MIKE (2015). "DEEPDREAM - A CODE EXAMPLE FOR VISUALIZING NEURAL
NETWORKS". GOOGLE RESEARCH. ARCHIVED FROM THE ORIGINAL ON 2015-07-08.
[2] LAFRANCE, ADRIENNE (2015-09-03). "WHEN ROBOTS HALLUCINATE". THE ATLANTIC. RETRIEVED 24 SEPTEMBER 2015.
