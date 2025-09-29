# TCSMAF

## Project Profile

This repository is used for demonstrations and testing based on the HieWoodNet framework. We have uploaded sample image.

## Method Overview

We propose a woodblock style transfer network, HieWoodNet, which is based on multi-scale semantic representation and hierarchical style modeling. First, we design a Content-Aware Positional Encoder, combined with the Transformer architecture, to perform multi-level position encoding on the input image, which strengthens the model's ability to express features of different scales and enhances the global structure perception ability, ensuring that the content structure of the original image is accurately preserved during the style transfer process. Secondly, we propose a HierStyle Encoder that can automatically learn rich style features from training data and carefully control each stage of the style transfer process, thereby enhancing the semantic and texture relevance of the generated image. The progressive decoder injects hierarchical style features while retaining the global semantic contour structure through multi-stage upsampling and cross-layer connections. Finally, in order to dynamically optimize the color embedding representation and effectively reduce the dependence on manual annotation, we introduce the ChromaNova Color Decoder. This module constructs a multi-dimensional color loss function that not only considers color contrast, but also pays attention to multiple aspects such as color distribution differences to comprehensively improve style matching.

## Code

We will upload the training scripts, testing code, and the complete dataset in future updates.
