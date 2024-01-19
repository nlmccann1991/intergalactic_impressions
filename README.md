# Intergalactic Impressions: How to Use Neural Style to Create SpaceX Impressionism
### A Project by Noel McCann

<img src="Intergalactic Impressions/Files/tf/Files/images/impression_space.png" style="width:550px;height:200px;">

AI is enabling content creation like never before. From LLMs dedicated to writing novels to using algorithms to create Drake songs from scratch, artists and creators are entering a new world of opportunities. Using the artistic style of Paul Gauguin, we will use his art style to reimagine images of SpaceX's Dragon initiative via Neural Style Transfer, an algorithm created by [Gatys et al. (2015).](https://arxiv.org/abs/1508.06576)

## This project will:
- Implement the neural style transfer algorithm 
- Generate Gauguin-esque images via the algorithm 
- Define a style cost function & a content cost function
- Enable others to experiment with this tool

## What is Neural Style Transfer, anyway?

Neural Style Transfer is a deep learning optimization technique that is gaining popularity amongst content creators. This transfer merges two images: a <strong>"content" image (C)</strong> and a <strong>"style" image (S)</strong>. Once merged, a <strong>"generated" image (G)</strong> is created, which combines the "content" of image C with the "style" of image S. 

One popular example is a Monet-style depiction of the Louvre. This combines a stock photo of the museum (content image) with the impressionist style of Claude Monet (style image):

<img src="Intergalactic Impressions/Files/tf/Files/images/louvre_generated.png" style="width:750px;height:200px;">

Download the iPYNB file here on GitHub. For the pre-trained models and all the items you need to run the tool on your device, visit Google Drive here: https://drive.google.com/drive/folders/1Jp6AuIIqbyRtoTs-MNhaPQO_JQg96JAt?usp=sharing
