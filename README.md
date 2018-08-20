# SketchGAN
Deep Convolutional Generative Adversarial Network (DCGAN) for generating pencil sketches
<img src="https://github.com/BrianSantoso/SketchGAN/blob/master/samples/79500_3.PNG" width="614">

Generated Sketches after 79500 training iterations

The training set consists of 1001 unique grayscale images of pencil sketches of birds, horses, butterflies, disney characters, male and female faces, flowers, hearts, hands, still life, and other miscellanious objects. The image data was also flipped across the vertical axis to produce a total of 2002 pencil sketches.

The final layer of the generator network utilizes a sigmoid function that is stretched by a factor of 5 (by scaling the input by 0.2). This allows for smooth pencil-like textures.

The generator's output after around 79.5k training iterations appears to have the most distinct outputs. As the network approaches 100k iterations, the figures become more intricate but seem to resemble 'doodles' more than sketches.

Samples from 100k iterations:

<img src="https://github.com/BrianSantoso/SketchGAN/blob/master/samples/100000_3.PNG" width="614">
<img src="https://github.com/BrianSantoso/SketchGAN/blob/master/samples/100000_4.PNG" width="614">
<img src="https://github.com/BrianSantoso/SketchGAN/blob/master/samples/100000_5.PNG" width="614">
