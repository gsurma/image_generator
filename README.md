<h3 align="center">
  <img src="assets/image_generator_icon_web.png" width="300">
</h3>

# Image Generator

Python notebook containing TensorFlow DCGAN implementation. It was trained on a [Simpsons Faces](https://www.kaggle.com/kostastokis/simpsons-faces) dataset.

<h3 align="center">
  <img src="assets/homer.gif">
</h3>

## Training
Here is a visualization of training with the following hyperparameteres.

	IMAGE_SIZE = 128
	NOISE_SIZE = 100
	LR_D = 0.00004
	LR_G = 0.0004
	BATCH_SIZE = 64
	EPOCHS = 300
	BETA1 = 0.5
	WEIGHT_INIT_STDDEV = 0.02
	EPSILON = 0.00005

<img src="assets/epochs.gif">

## Results

And some cherry-picked results.

<img src="assets/final_grid_500.png">


As expected, there were some funny-looking malformed faces as well.
<img src="assets/misc.png">