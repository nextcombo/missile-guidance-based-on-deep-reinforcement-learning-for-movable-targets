# Missile Guidance Based on Deep Reinforcement Learning for Movable Targets

Introduction In this paper, we focus on the calculation of guidance laws for intercepting maneuvering targets with lateral acceleration constraints. It is practically impossible to predict target maneuvers, so analytical solutions may be ineffective. We have proposed reward functions in reinforcement learning frameworks [1] for training guidance commands for such scenarios.
The guidance commands formulated using Proportional-Navigation-Guidance Law (PNG) are primarily due to their simplicity and effectiveness [2] [3]. Here, the guidance command is the lateral acceleration of the missile, its sole purpose is to reduce the relative distance between the missile and the target. Based on linearization models [7], many PNG laws can be used to control terminal collision angles [5] and collision times [6]. Real-world guidance problems are highly time-varying, nonlinear in nature, and are subject to numerous practical limitations. Therefore, using PNG laws in such cases is very challenging because they approximate the model.
On the other hand, from the Generalized Approximation Theorem [8], it is known that neural networks with one or more hidden layers can approximate any continuous function within a certain range. They can be used to approximate such nonlinear models, taking into account other uncertainties, such as aerodynamics.
The design of model-based guidance algorithms takes into account the fact that all dynamic behaviors of the model are fully known. The performance of such a guidance law depends on the accuracy of the model used. Data-driven learning algorithms can even help select suboptimal models. Therefore, in the presence of model uncertainty, data-driven algorithms can show performance improvements compared to only model-based methods. Many interesting tasks, especially physical control tasks, involve continuous (real-valued) and high-dimensional action spaces [9]. Guidance commands are needed, which can actually be used in our real scenario using deep reinforcement learning by using deep neural network function approximators to estimate the action value function.
Article illustration
Conclusion: The deep reinforcement learning (DRL) technique is employed to generate missile target interception guidance commands. A reward function based on zero-effort miss distance and relative distance rate is proposed for training the DDPG agent. It can be seen how these reward functions form the guidance commands. Furthermore, it demonstrates that using the known PNG rules to train the guidance gain ratio directly results in better performance without prior knowledge. The experimental section verifies the effectiveness of this method.

## Images

![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](01.jpg)
![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](02.jpg)
![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](03.jpg)
![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](04.jpg)
![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](05.jpg)
![[Missile Guidance] Motivated Target Missile Guidance and Control Based on Deep Reinforcement Learning [with Python code attached]](06.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
