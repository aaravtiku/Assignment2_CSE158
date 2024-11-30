
(i) Our group has selected a publicly available dataset created by Professor Julian McAuley, which  provides both plain-text feedback and aspect-specific numeric ratings for beers. This dataset has been used extensively in the fields of recommendation systems and sentiment analysis, such detailed information allows our group for a more detailed exploration of user preferences across beers.

(ii) There have already been a lot of previous researches that used similar datasets to conduct detailed sentiment and aspect analysis. We’ve collected two research papers that’s related to our dataset. First of all, in the paper, "Learning Attitudes and Attributes from Multi-Aspect Reviews" by McAuley et al., the authors use datasets like BeerAdvocate and RateBeer to model aspects of products like taste, feel, and overall impressions. Their study highlights the importance of separating content words which describe a particular aspect, away from those emotion words that express the user’s feeling about those aspects, and this is critical to accurately interpreting and summarizing reviews. Another research paper is called "From Amateurs to Connoisseurs: Modeling the Evolution of User Expertise through Online Reviews." This paper analyzes reviews to model user experience over time, demonstrating how tastes evolve as users gain experience and become more familiar with the products. This dataset is particularly beneficial for studies that aim to understand both product features and the progression of user preferences.

(iii) The state-of-the-art methods currently employed to study multi-aspect review data involve sophisticated latent factor models tailored to specific predictive goals. In the paper "Learning Attitudes and Attributes from Multi-Aspect Reviews," the authors use a latent factor model to predict aspect-specific ratings by capturing the interactions between user preferences and product features. The latent factors represent underlying dimensions such as taste or feel, providing a more nuanced understanding of user sentiment across different aspects of a product. Additionally, topic modeling is utilized to separate content words from sentiment words, which aids in delivering accurate aspect-level predictions. On the other hand, the paper "From Amateurs to Connoisseurs: Modeling the Evolution of User Expertise through Online Reviews" employs latent factor models to capture the evolution of user preferences over time. These models include two approaches: a uniform evolution model, which assumes a constant rate of experience change, and a learned evolution model, which adapts to each user's unique rate of experience acquisition. By incorporating user-specific latent parameters, the learned evolution model captures individual user trajectories more accurately, thereby improving the quality of recommendations. These methods represent the state-of-the-art in modeling multi-aspect sentiment and evolving user preferences, allowing for more precise predictions tailored to both product features and user expertise growth.

(iv) Conclusion, TBD