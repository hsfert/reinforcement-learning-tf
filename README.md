# Reinforcement Learning Project

## Reinforcement learning project for Atari games

It is cloned from this repo by [dennybritz](https://github.com/dennybritz/reinforcement-learning), which provides the exercise for the famous [David Silver's Reinforcement Learning Course](https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLqYmG7hTraZBiG_XpjnPrSNw-1XQaM_gB).

In this repo, I have made the following changes to the code:

1. The tensorflow 1.x code is changed to tensorflow 2.x and is more intuitive now.
2. I have translated the BDQN (essentially just add a Bayesian linear layer at the end) by [kazizzad](https://github.com/kazizzad/BDQN-MxNet-Gluon) and translated the MxNet code into tensorflow code. (See BDQN.ipynb)

The updated gym/ale-py version requires a lot more dependency and so better to restrict the package versions to:
- gym==0.21.0
- atari-py==0.7.1
