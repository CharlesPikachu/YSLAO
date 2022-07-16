## Introduction

The official repository for "[You Should Look at All Objects]()".


## Abstract

Feature pyramid network (FPN) is one of the key components for object detectors.
However, there is a long-standing puzzle for researchers that the detection performance of large-scale objects are usually suppressed after introducing FPN.
To this end, this paper first revisits FPN in the detection framework and reveals the nature of the success of FPN from the perspective of optimization.
Then, we point out that the degraded performance of large-scale objects is due to the arising of improper back-propagation paths after integrating FPN.
It makes each level of the backbone network only has the ability to look at the objects within a certain scale range.
Based on these analysis, two feasible strategies are proposed to enable each level of the backbone to look at all objects in the FPN-based detection frameworks.
Specifically, one is to introduce auxiliary objective functions to make each backbone level directly receive the back-propagation signals of various-scale objects during training.
The other is to construct the feature pyramid in a more reasonable way to avoid the irrational back-propagation paths.
Extensive experiments on the COCO benchmark validate the soundness of our analysis and the effectiveness of our methods.
Without bells and whistles, we demonstrate that our method achieves solid improvements (more than 2%) on various detection frameworks: one-stage, two-stage, anchor-based, anchor-free and transformer-based detectors.


## Model Zoo

Coming soon.