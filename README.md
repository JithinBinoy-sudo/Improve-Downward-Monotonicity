# Improve-Downward-Monotonicity

**ABOUT**
Monotonicity reasoning remains a key challenge in natural language inference (NLI), especially for downward-entailing contexts involving negation or subset reasoning. While transformer models such as BERT and DistilBERT perform well on general inference, they often fail on downward monotonicity. This paper proposes PolarityDistilBERT, a polarity-aware variant of DistilBERT that incorporates explicit [UP] and [DOWN] tokens to signal entailment direction. A polarity-balanced dataset was constructed from curated examples and subsets of the MED and HELP benchmarks, ensuring equal representation of upward and downward contexts. Experiments show that PolarityDistilBERT significantly improves downward entailment accuracy (86%) compared to baselines, though with a modest decline in upward performance. Attention analysis confirms polarity tokens act as effective structural cues. These results demonstrate that polarity-aware modeling can mitigate biases in pretrained models and enhance logical reasoning in NLI, offering a promising step toward more robust and interpretable inference systems.

**HOW TO RUN**
1) Go to the google colab link provided
2) Run the cells
3) Output will be displayed
