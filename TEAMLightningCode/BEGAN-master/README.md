# BEGAN: Boundary Equibilibrium Generative Adversarial Networks


GAN training is rife with problems such as non-convergence(model parameters never converge), model collapse(limited sample variety), diminished gradient(discriminator pushes down on the generator that it learns nothing)

BEGAN is an autoencoder based GAN trained using Wasserstein distance and has ideas borrowed from control theory infused into the process. It essentially balances the generator and discriminator during training and provides an approximate measure of convergence and tunable image diversity and quality


Credits:

Major portion of the models and training process has been adapted from https://github.com/artcg/BEGAN
