# Velocity-Obstacle using Sampling
<img width="463" alt="VO-1" src="https://user-images.githubusercontent.com/32260835/120100006-8271b800-c14f-11eb-9e3d-8f216e8b7bc7.png">

## Obstacle Avoidance using Collision Cone

* A single holonomic robot is supposed to reach its goal by avoiding collision with moving obstacles. We use velocity obstacle formulation to perform goal reaching obstacle avoidance in a dynamic environment.
* We try to calculate an optimal velocity such that the agent reaches the goal while avoiding the obstacles using collision cone constraints. 
* We perform a sampling based method to generate different velocities within a range and then find the optimal velocity with minimum cost.
