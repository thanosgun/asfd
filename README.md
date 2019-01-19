import gym
import universe

env = gym.make('flashgame.CoasterRacer-v0')
observation_n = env.reset()

while True:
  action_n = [[('KeyEvent', 'ArrowUp', True)] for ob in observation-n]
  observation_n, reward_n, done_n, info = env.step(action_n)
  env.render()
