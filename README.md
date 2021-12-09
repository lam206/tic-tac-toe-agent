# tic-tac-toe-agent

This is a quick implementation of a reinforcement learning agent only using numpy. The agent is trained with Monte Carlo control and epsilon-soft policies. Something interesting I found out is that increasing epsilon from 0.05 to 0.15 significantly decreases the number of games the agent needs to play to learn to play optimally. With 0.15 it knows how to play optimally after 10,000 games. With 0.05, even 100,000 games are not enough.

The agent plays during training against a random-trainer, which just picks a random move. 

Using a deterministic policy with exploring starts would probably be better and more efficient. I chose to do it with Monte carlo soft-policies for fun.
