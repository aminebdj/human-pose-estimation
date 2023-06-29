# Human pose estimation

This code was built on top of <a href="https://github.com/anibali/pytorch-stacked-hourglass/tree/master">Stacked-Hour-Glass</a>.

Human Pose Estimation (HPE) seeks to find human
body components and construct human body representations (e.g., skeletons) from input data such as photographs
and videos. It has gained popularity over the last decade
and has been used in various applications such as human-computer interaction, entertainment, and virtual reality. Although recently developed deep learning-based solutions
have achieved high performance in human pose estimation,
challenges remain due to a lack of training data, depth ambiguities, and occlusion. In this paper, we represent our
modification of Stacked Hourglass Networks [5], which significantly increases performance by 13% regarding the model
speed with an increase in accuracy by around 0.7%
