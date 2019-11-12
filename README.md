# SIAM Parallel Processing for Scientific Computing 2020 Poster

## SemanticModels.jl: A Framework for Automatic Composition of Scientific Models Across Domains

Compile in R with `rmarkdown::render("poster.rmd")`

### Abstract

Scientific progress comes from adapting and extending models from prior work to
address new problems. However, this ideal workflow is difficult primarily because
of the informal or inconsistent representation of models.
This problem is exacerbated in fields outside of computer science where
scientific models are formulated in informal languages. We propose `SemanticModels.jl`, a
category theory-based framework for defining meta-modeling tasks such as model
augmentation and model selection along with semantic information extraction. 
We illustrate the major features of `SemanticModels.jl` including the representating
models as wiring diagram, extending and composing models with algebraic operations, 
and generating executable code of the resulting model. These features are demonstrated by
constructing a model of mosquito borne illness in humans along with predator-prey dynamics 
between mosquitos and birds to study the effects of predator species on the control of mosquito borne illnesses.
Through the careful application of category theoretic ideas to scientific computing,
general patterns in scientific modeling languages and frameworks can be axiomatized and these formalizations
can be exploited to improve scientific computing research and development processes.
