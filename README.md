# Say My Name: a Model's Bias Discovery Framework (SaMyNa)
Source code supporting the paper "Say My Name: a Model's Bias Discovery Framework" (TMLR, Nov. 2025).

## Abstract
Due to the broad applicability of deep learning to downstream tasks and end-to-end training capabilities in the last few years, increasingly more concerns about potential biases to specific, non-representative patterns have been raised. Many works focusing on unsupervised debiasing leverage the tendency of deep models to learn “easier” samples, for example by clustering the latent space to obtain bias pseudo-labels. However, their interpretation is not trivial as it does not provide semantic information about the bias features. To address this issue, we introduce “Say My Name” (SaMyNa), a tool to identify semantic biases within deep models. Unlike existing methods, our approach focuses on biases learned by the model, enhancing explainability through a text-based pipeline. Applicable during either training or post-hoc validation, our method can disentangle task-related information and propose itself as a tool to analyze biases. Evaluation on typical benchmarks demonstrates its effectiveness in detecting biases and even disclaiming them. When sided with a traditional debiasing approach for bias mitigation, it can achieve state-of-the-art performance while having the advantage of associating a semantic meaning to the discovered bias.


## Code and BibTeX coming soon
