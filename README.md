OpenAI_Retro_contest_Modulabs
=============================

This is for OpenAI Retro contest ( Making sonic agent with reinforcement learning algorithm ), 오픈에이아이 소닉 대회를 위한 모두의연구소 깃허브 입니다.
### bloging

1편 : OpenAIRetro Contest 참여 및 소닉 설치방법 https://wonseokjung.github.io//openairetro/update/Retro-1/

제2편 Open AI Retro 소닉 대회 : 대회 목표, 대회 참여, 에이전트 제출

https://wonseokjung.github.io//openairetro/update/openai-retro-2/

https://contest.openai.com/

### Paper to Read:

Tech report : https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/retro-contest/gotta_learn_fast_report.pdf


https://arxiv.org/abs/1511.05952
priority
https://arxiv.org/pdf/1511.06581.pdf
dueling
https://arxiv.org/abs/1706.10295
noisy
https://arxiv.org/abs/1707.06887
distribution

### Links 

Baselines
https://github.com/openai/retro-baselines


Retro Contest

https://blog.openai.com/retro-contest/

Gotta Learn Fast: A New Benchmark for Generalization in RL https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/retro-contest/gotta_learn_fast_report.pdf

gym retro:

https://github.com/openai/retro

### Collaborator

김경환

### 참고해야할 anyrl code

from anyrl.algos import DQN

https://github.com/unixpickle/anyrl-py/blob/master/anyrl/algos/dqn.py

from anyrl.envs import BatchedGymEnv

https://github.com/unixpickle/anyrl-py/blob/b43f0728400fd5c01daf4ae110c797622d0c9ddb/anyrl/envs/gym.py

from anyrl.envs.wrappers import BatchedFrameStack

#### BatchedFrameStack

https://github.com/unixpickle/anyrl-py/blob/8a1ab680e56be8de435b0b8fff1fc48d7a37463a/anyrl/envs/wrappers/batched.py

from anyrl.models import rainbow_models

https://github.com/unixpickle/anyrl-py/blob/8e119ca25724d537db3e620bd922f39a2ac61ea4/anyrl/models/dqn_dist.py

from anyrl.rollouts import BatchedPlayer, PrioritizedReplayBuffer, NStepPlayer

#### batchplayer: 

https://github.com/unixpickle/anyrl-py/blob/1543af96346293e90ff30b6912dab66c681c2ed1/anyrl/rollouts/players.py

#### PrioritizedReplayBuffer

https://github.com/unixpickle/anyrl-py/blob/5e3fed0b0e249dcd01d844e4a9a47bb80b990699/anyrl/rollouts/replay.py


#### NStepPlayer


https://github.com/unixpickle/anyrl-py/blob/1543af96346293e90ff30b6912dab66c681c2ed1/anyrl/rollouts/players.py


from anyrl.spaces import gym_space_vectorizer

https://github.com/unixpickle/anyrl-py/blob/8a1ab680e56be8de435b0b8fff1fc48d7a37463a/anyrl/spaces/gym.py



