+++
title = "Regularisation Can Mitigate Poisoning Attacks: A Novel Analysis Based on Multiobjective Bilevel Optimisation"
date = 2020-02-01
authors = ["Javier Carnerero-Cano", "Luis Muñoz-González", "Phillippa Spencer", "Emil C. Lupu"]
publication_types = ["3"]
abstract = "Machine Learning (ML) algorithms are vulnerable to poisoning attacks, where a fraction of the training data can be manipulated to deliberately degrade the algorithms' performance. Optimal poisoning attacks, which can be formulated as bilevel optimisation problems, help to assess the robustness of learning algorithms in worst-case scenarios. However, current attacks against algorithms with hyperparameters typically assume that these hyperparameters are constant and thus ignore the effect the attack has on them. In this paper, we show that this approach leads to an overly pessimistic view of the robustness of the learning algorithms tested. We propose a novel optimal attack formulation that considers the effect of the attack on the hyperparameters by modelling the attack as a multiobjective bilevel optimisation problem. We apply this novel attack formulation to ML classifiers using L2 regularisation and show that, in contrast to results previously reported in the literature, L2 regularisation enhances the stability of the learning algorithms and helps to partially mitigate poisoning attacks. Our empirical evaluation on different datasets confirms the limitations of previous poisoning attack strategies, evidences the benefits of using L2 regularisation to dampen the effect of poisoning attacks and shows that the regularisation hyperparameter increases as more malicious data points are injected in the training dataset."
featured = true
publication = "*arXiv preprint arXiv:2003.00040*"
url_pdf = "https://arxiv.org/abs/2003.00040"
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
caption = "Effect of regularisation on a synthetic classification problem."
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

