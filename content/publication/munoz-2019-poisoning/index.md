+++
title = "Poisoning Attacks with Generative Adversarial Nets"
date = 2019-09-01
authors = ["Luis Muñoz-González", "Bjarne Pfitzner", "Matteo Russo", "Javier Carnerero-Cano", "Emil C. Lupu"]
publication_types = ["3"]
abstract = "Machine learning algorithms are vulnerable to poisoning attacks: An adversary can inject malicious points in the training dataset to influence the learning process and degrade the algorithm's performance. Optimal poisoning attacks have already been proposed to evaluate worst-case scenarios, modelling attacks as a bi-level optimization problem. Solving these problems is computationally demanding and has limited applicability for some models such as deep networks. In this paper we introduce a novel generative model to craft systematic poisoning attacks against machine learning classifiers generating adversarial training examples, i.e. samples that look like genuine data points but that degrade the classifier's accuracy when used for training. We propose a Generative Adversarial Net with three components: generator, discriminator, and the target classifier. This approach allows us to model naturally the detectability constrains that can be expected in realistic attacks and to identify the regions of the underlying data distribution that can be more vulnerable to data poisoning. Our experimental evaluation shows the effectiveness of our attack to compromise machine learning classifiers, including deep networks."
featured = true
publication = "*arXiv preprint arXiv:1906.07773*"
url_pdf = "https://arxiv.org/abs/1906.07773"
keywords = "adversarial machine learning"

reading_time = false
share = false
profile = false
commentable = false
editable = false

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
[image]
placement =  1
caption = "Example of pGAN on Fashion-MNIST dataset."
focal_point = "Center"
preview_only = false

[related]
threshold = 80.0
includeNewer = true
toLower = false

  [[related.indices]]
  name = "keywords"
  weight = 100.0

  [[related.indices]]
  name = "date"
  weight = 0.0

+++

