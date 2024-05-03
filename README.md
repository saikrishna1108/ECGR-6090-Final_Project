##Navigating Uncertainty: Applications of
Adaptive Decision-Making from the Eater’s
Perspective


In the strategic and interactive ”Mover and
Eater” game, the Eater’s primary challenge is to accurately
discern and consume bananas from the true goal, based on
observations of the Mover’s behavior who knows the true
goal but attempts to deceive. To effectively tackle this chal-
lenge, we implement a multi-faceted reinforcement learning
approach, employing Monte Carlo First Visit, Temporal
Difference (TD) Learning, and Deep Q-Learning algo-
rithms. These methodologies are chosen for their strengths
in dealing with partial observability and the necessity for
strategic decision-making based on accumulated experience
rather than immediate rewards.
Monte Carlo First Visit estimation provides the founda-
tion by evaluating the expected returns by averaging the
sampled returns, thus offering a direct method to learn
the value of each state without requiring a model of the
environment’s dynamics. This method is particularly useful
in environments where the rewards are delayed, as it
calculates returns from the start of the game until the
end, providing a comprehensive understanding of long-
term strategy effectiveness.
Temporal Difference Learning, on the other hand, intro-
duces a model-free algorithm that combines the sampling
of Monte Carlo with the bootstrapping of Dynamic Pro-
gramming. This approach updates estimates based in part
on other learned estimates, without waiting for a final
outcome, thus allowing the Eater to learn more efficiently
from each individual step rather than waiting until the end
of an episode
