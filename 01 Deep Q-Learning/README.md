# Deep Q-Learning

This lesson looks at teaching a model (or agent) how to react to its environment to achieve a goal. The model tries to predict the future reward for a discrete action space, and chose the action with the highest predicted future reward. The reason for this is because we may not have the immediate reward for each action, and so the model needs to look further into the future to judge the benefit of the move. We will be using the OpenAI Gym Cartpole-v1 environment, where the agent needs to move the cart forward or backward to balance a freely rotating pole. 

To set up: `pip install -r requirements.txt`

The training code is in `training.ipynb`. Take a look, but fair warning, the training time is very long.<br>

Run `python test.py` to see the model in action. Note that this will not work on Codespaces or a similar web-based development environment. 

To understand the theory behind Q-learning and Deep Q-Learning, check out this [video](https://www.youtube.com/watch?v=x83WmvbRa2I)<br>
You can also check out the real-world application in this [video](https://youtu.be/Cym3rEvI9yo)

<br>

To practice further, check out some of the other [OpenAI Gym environments](https://gymnasium.farama.org/environments/classic_control/). Most have a Discrete action space (fixed number of moves, like the Cartpole), which means you can use Deep Q-Learning 