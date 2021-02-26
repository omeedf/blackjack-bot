# Blackjack-Bot
Creating a blackjack player using reinforcement learning.

Blackjack, also known as twenty-one, is a popular card game that is played around the world. Each player competes against the dealer to have the better hand -- one where the sum of the card values are closest to 21 without exceeding 21.

This blackjack agent starts by playing blackjack using completely random stratgy, and utilizes a machine learning technique called reinformcement learning to independetely derive the optimal blackjack strategy, sometimes referred to as Basic Strategy. After each move, the agent makes slight changes to its strategy depending on the result of the round eventually reaching Basic Strategy. While the dealer will always have an advantage in the game of blackjack, Basic Strategy is able to reduce the dealer's edge to around 0.5%.

The table displayed below is generated by the blackjack agent and shows the decision it has found to be optimal given a starting hand of two cards and the dealer's single up card. Compared to existing Basic Strategy tables, the agent was able to generate a table that is nearly 90% accurate.

![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
