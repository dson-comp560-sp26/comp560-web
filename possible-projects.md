# Possible research projects and mini-projects

In no particular order:
* Investigate migration to nanochat
* Replicate anything from Feng23 or Baeumel25
* The [first research experiment](first-research-expt/first-research-expt.md) page describes how to create a transformer model based on a continuous stream of input, then assess the ability of the model to generate a continuous stream of output similar to the input. For many of the proposed experiments this semester, it will be preferable train the transformer model to produce short _responses_ in response to short _inputs_. That is, all inputs and outputs are relatively short rather than being a continuous stream. Create a framework for conducting experiments with this type of model.
* Get a robust addition model working and clearly characterize the points at which it fails
  - then, train it with chain of thought -- do we need more, less, or about the same resources?
  - then, give it scratch space to develop its own chain of thought -- Can we identify any resource savings from doing it this way?
* Figure out how to design certain GPTs by hand, then implement and test in PyTorch, e.g.:
  - copy an n-character input (for, say, n=3)
  - reverse an n-character input (for, say, n=3)
  - n-digit binary/ternary/decimal addition
  - markov chain and HMM
* For all models in the previous bullet point, experiment with training a model that is as similar as possible but created completely automatically from training.
* Mentor high school student.
* Mentor one or both of our first-year students.
* Experiment with training our simple character-level models on GPUs. Determine whether GPUs are a significant benefit for this type of model. If so, how can we best take advantage of them? Analyze the financial costs and benefits, then make a recommendation on how to proceed.
  - This is a complex question that depends on the size of the models we are using. So the analysis needs to employ a range of different sizes for the models.

