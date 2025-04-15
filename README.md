<img src="docs/logo.png" width="300"/>

# How to Train a Robot and Still Sleep at Night

##### by Francesco Giuseppe Gillio
###### Department of Control and Computer Engineering
###### Politecnico di Torino

## Reference Paper
- [How to Train a Robot and Still Sleep at Night](https://github.com/305909/gym-hopper-reinforcement/blob/main/docs/gym-hopper-reinforcement-ACM.pdf)

---

## Table of Contents

- [What’s the Problem? (Abstract)](#whats-the-problem-abstract)
- [The Tools of the Trade (Algorithms)](#the-tools-of-the-trade-algorithms)

---

## What’s the Problem? (Abstract)

This study takes a closer look at how reinforcement learning (RL) agents can learn to hop like pros—on one leg. Using the Hopper environment from OpenAI Gym and the MuJoCo physics engine, we task a robotic monopod with learning to jump, stay upright, and move forward efficiently. It sounds simple, but getting robots to learn this kind of behavior in a simulated world—and then do it in the real one—is still one of the hardest nuts to crack in modern AI.
    
To make progress, we put a set of policy gradient algorithms under the microscope: REINFORCE, Actor-Critic, and the widely used Proximal Policy Optimization (PPO). We examine how well they train agents to handle the challenge, weighing their strengths and limits. But learning in a perfect simulation isn't enough. Real-world physics is messy, unpredictable, and full of surprises. That's why we also explore domain randomization—specifically, an advanced method called Domain Randomization Optimization IDentification (DROID). It shakes up the simulation conditions to better prepare agents for the real deal.
    
By combining policy gradients with robust domain randomization, this work takes a step toward narrowing the infamous “reality gap” between simulation and the physical world. The result? Smarter, more adaptable robots that aren’t thrown off by a little chaos. Along the way, we lay the foundation for sharper RL strategies and smarter ways to bridge the virtual-to-real divide in robotics.

---

## The Tools of the Trade (Algorithms)

Play time starts here.

1. Fire this up in your notebook:

```python
!git clone https://github.com/305909/gym-hopper-reinforcement.git
!bash gym-hopper-reinforcement/src/requirements.sh
```

2. Run the models and see what happens:

```python
!python /content/gym-hopper-reinforcement/src/... # search and find
```

Boom. **Game over**.

---

> *“If your code always makes sense to you, you're either an idiot — or not thinking hard enough.”*

That’s what this project is about. Now go dig in.

— *F.G.G. (still writing code, as always)*
