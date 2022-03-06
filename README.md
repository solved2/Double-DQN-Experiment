# Double DQN Experiment Repository

OpenAI gym의 CartPole을 DQN과 Double DQN으로 각각 학습한 뒤, 논문의 <code>Figure 3</code>을 graphing하여 비교해봅니다.

# Plot Result

- Double DQN
  <img src="https://user-images.githubusercontent.com/79636473/156908589-24be029a-3ce1-4006-b862-e73fcf9fb49f.png">

- DQN
  <img src="https://user-images.githubusercontent.com/79636473/156908590-9218d3df-13b3-4922-b2bd-c0e90c4b6d0e.png">

# Conclusion

- 논문의 결과와 마찬가지로, DQN이 학습 중 overestimation을 일으키는 현상을 관찰할 수 있음.

- Double DQN의 경우 DQN에 비해 확실히 overestimation의 경향이 적은 것을 볼 수 있음.

- 학습을 마친 후 얻은 average return 값의 경우에도, DQN보다는 Double DQN이 더 높은 값을 보임.

- 학습 중 shaded area의 폭도 Double DQN이 DQN보다 작은 것을 볼 수 있음.
