# Project VanGogh_GANs (Generative Adverserial Networks)
This is a personal project is to explore and understand the workings of Generative Adverserial Networks (GANs). The goal is to generate real-like(faux) Van Gogh paintings using GANs.

## The Dataset:
The Dataset comprises of 144 jpeg color images of paitings from the Saint Remy collection by Van Gogh.

## Repository Structure:
VanGogh_GANs_64x64 contains the ipynb files where the images are reduced to size 64x64x3.
VanGogh_GANs_128x128 contains the ipynb files where the images are reduced to size 128x128x3.

The original images were of sizes 2065x2043x3. Due to constraints in compute resources, the images had to be reduced to lower quality.  

## The MODEL:
The GANs model consists of a discriminator and a generator that compete against each other.
The generator tries to create images that look like real paintings to fool the discriminator.
The discriminator tries to detect real paintitng images and the faux generator created painting images.

The end result turned out to be Van Gogh-esque styled abstract paintings. Further tuning is underway to make the model better to get more realistic outputs. ALthough the current state of results is already quite promising. Stay tuned for further advancement and improvement to this model.
