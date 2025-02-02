__Official Code for the Paper "Transformers Can Do Bayesian Inference"__

We train Transformers to do Bayesian Prediction on novel datasets for a large variety of priors. For more info read our [paper](https://arxiv.org/abs/2112.10510).
You can play with our model in an interactive [demo](https://huggingface.co/spaces/samuelinferences/transformers-can-do-bayesian-inference) with a GP prior and compare it to the ground truth GP posterior, as described in the paper's section 5.1.

For insights into experiments, please see our `notebooks` folder. From where most experiments, besides some baselines are started.

Training the transformers can be quickly done for all tasks considered, but we still provide models for the tabular tasks as convenience to be able solve new tabular tasks out-of-the-box.
