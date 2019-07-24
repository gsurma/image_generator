<h3 align="center">
  <img src="assets/image_generator_icon_web.png" width="300">
</h3>

# Image Generator

Python notebook containing TensorFlow DCGAN implementation. It was trained on a [Simpsons Faces](https://www.kaggle.com/kostastokis/simpsons-faces) dataset.

<br>

Check out corresponding Kaggle kernel: [Image Generator](https://www.kaggle.com/greg115/image-generator-dcgan-the-simpsons-dataset).

Check out corresponding Medium article:

[Image Generator - Drawing Cartoons with Generative Adversarial Networks](https://towardsdatascience.com/image-generator-drawing-cartoons-with-generative-adversarial-networks-45e814ca9b6b)

<h3 align="center">
  <img src="assets/homer.gif">
</h3>

## DCGAN
Network architecture by [Radford et al., 2015](https://arxiv.org/abs/1511.06434).
<img src="assets/model.png">

## Training
Visualization of training with the following hyperparameteres.
<img src="assets/epochs.gif">

	IMAGE_SIZE = 128
	NOISE_SIZE = 100
	LR_D = 0.00004
	LR_G = 0.0004
	BATCH_SIZE = 64
	EPOCHS = 300
	BETA1 = 0.5
	WEIGHT_INIT_STDDEV = 0.02
	EPSILON = 0.00005


## Results

Cherry-picked generated samples.

<img src="assets/final_grid.png">


As expected, there were some funny-looking malformed faces as well.
<img src="assets/misc.png">

## Author

**Greg (Grzegorz) Surma**

[**PORTFOLIO**](https://gsurma.github.io)

[**GITHUB**](https://github.com/gsurma)

[**BLOG**](https://medium.com/@gsurma)

<a href="https://www.paypal.com/paypalme2/grzegorzsurma115">
  <img alt="Support via PayPal" src="https://cdn.rawgit.com/twolfson/paypal-github-button/1.0.0/dist/button.svg"/>
</a>

