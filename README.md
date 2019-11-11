# SIAM Parallel Processing for Scientific Computing 2020 Poster

## SemanticModels.jl: A Framework for Automatic Composition of Scientific Models Across Domains

Compile in R with `rmarkdown::render("poster.rmd")`

### Abstract

Scientific progress comes from adapting and extending models from prior work to
address new problems. However, the adaptation of this ideal workflow is
difficult primarily because of the non-consistent representation of models.
This problem is exacerbated in fields outside of computer science where
programmatic models are less structured. We propose `SemanticModels.jl`, a
category theory-based framework for defining meta-modeling tasks such as model
augmentation and semantic information extraction. We demonstrate the usage of
`SemanticModels.jl` in threefolds: First, we demonstrate the conversion of
predator-prey and infectious disease models to wiring diagram representations.
Next, we show the extension and composability of the two models. Finally, we
generate executable code of the new model that takes into account the spread of
Malaria and predator-prey interactions and visualize the results.
