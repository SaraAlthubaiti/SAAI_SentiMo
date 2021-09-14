# SentiMo

![Alt Text](Gallery.gif)

<h3 align="center">~When feelings can be painted~</h3>

## Inspiration

Everyday, billions of WhatsApp messages, tweets on Tweeter are released from our smart devices as we try to express our feelings and emotions. This amount of data derived from social media network lead us to ask ourselves: what if we could use ML algorithms to embody our complaints or feelings about public topics such as COVID-19? How would our emotions look like if we gave the algorithm brushes and paint to draw our sentiment into pieces of art?

## What it does?

SentiMo captures the public sentiment about controversial/popular topics in a mosaic art form. Through the use of sentiment analysis, we will attempt to record the public sentiment. Once the sentiment is captured, we will illustrate it in an art form through the use of a mosaic GAN where the texture will be the generated art from text that are more frequently expressed in each sentiment. The end result will be a piece of art that is a given image (pertaining to the topic of interest) re-produced/constructed in a mosaic form whose texture is the generated text to art from public sentiment. Finally, turn suffering into an audible impact by coding a protein sequence by its frequency which related to a specific topic (ex. COVID-19) to generate a symphony using MusicGAN.

## How we built it?

- Preprocess and analyze tweets.
- Generate text2art using StyleGAN.
- Generate mosaic image using (CAN+GAN).
- Mask the mosaic into digital image.

## Challenges we ran into

- Optimizing the dataset.
- Training and lack of medical data.

## Accomplishments that we're proud of

- Choosing the idea that originated and is reflected by our field of research.
- Incorporate different GANs and CANs models to achieve our goal.
- Make room for creativity by investigate turning a DNA sequence to music by its frequency.

## What we learned

- Working with sentiment analysis.
- Using pretrained models for generating images from text.
- Visualize our work in different artistic ways.

## What's next for SentiMo

- Release SentiMo online virtual gallery for all audiences!
- Optimize the deep learning network of SentiMo algorithm
- Produse more meaningful images on different illness
- Generate a complete symphony with different DNA sequence
- Keep improving and learning more
