# Blackjack_RL
Reimagining Playing Blackjack Using RL

![image](https://github.com/user-attachments/assets/c6ca3aea-720c-46d9-a6a6-47efef8cab42)

This project explores the application of the Double Q-learning algorithm to optimize blackjack strategy. By implementing and comparing 125 combinations of hyperparameters (gamma, alpha, epsilon), we aim to address the overestimation bias inherent in traditional Q-learning methods. Our approach involved iterative training over 20,000,000 episodes, followed by evaluation against baseline and random strategies. The performance metrics—wins, losses, cumulative winnings, and win percentage—were visualized to highlight the effectiveness of our strategy.

Results indicate that specific hyperparameter combinations significantly enhance performance, achieving win percentages over the optimal startegy. The Double Q-learning algorithm demonstrated its potential to refine decision-making in uncertain environments, suggesting broader applicability in strategic AI deployment. This work contributes to the understanding of reinforcement learning applications in gaming, offering insights into more stable and reliable learning outcomes in blackjack.

In comaprison to basic startegy (optimal strategy):
Wins Comparison: Our strategy consistently achieved higher wins compared to the baseline and random strategies.
Losses Comparison: Our strategy maintained lower losses than the baseline and random strategies.
Cumulative Winnings Comparison: Our strategy outperformed in cumulative winnings.
Percentage Comparison: Our strategy demonstrated a higher win percentage.
