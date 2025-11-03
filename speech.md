Slide 1:
Good morning everyone, I'm Mattia Piccinini, a postdoctoral researcher at the Technical University of Munich, in Germany. Today, I'm excited to present a summary of my dissertation, titled "Artificial Drivers for Online Time-Optimal Vehicle Trajectory Planning and Control", which I received from the University of Trento in Italy in 2024. 

26 sec

Slide 2:
So, autonomous vehicle racing is becoming a useful testing ground for autonomous driving. Indeed, circuits are safe environments where we can reproduce high-speed emergency scenarios.
However, open challenges remain as we see in this video, particularly in real-time decision-making with adversarial agents, and in planning and control with the nonlinear vehicle dynamics.

31 sec

Slide 3:
To address these challenges, I propose a new artificial race driver, which learns the vehicle dynamics and the maximum performance from data, using a multi-round closed-loop training approach. It then performs online minimum-time trajectory planning with a new learning-based kineto-dynamical model predictive controller, and finally tracks the planned trajectory with new model-structured NNs that embed prior knowledge of the vehicle dynamics into their architecture.

40 sec

Slide 4:
When applied to high-fidelity vehicle simulators, in the final learning rounds, our artificial driver reaches lap times close to the MLT-DT benchmark, which is an offline minimum-lap-time solution computed with full knowledge of the vehicle and circuit. In contrast, our driver has no prior knowledge; it learns from data and drives in real time. The remaining gap is just 0.3 to 0.7 seconds, comparable to the difference among Formula 1 drivers.

40 sec

Slide 5:
And interestingly, our driver generalizes zero-shot to unseen circuits, achieving lap times again close to the MLT-DT reference. 

13 sec

Slide 6:
I deployed the artificial driver to real small-scale autonomous vehicles, and in high-fidelity simulators. We are now deploying the driver on our full-scale autonomous race car.

18 sec

Slide 7:
The framework can also deal with dynamic obstacle avoidance, thanks to new neural motion primitives within a sampling-based planning algorithm, which can deal with multiple opponents in real-time.

Slide 8:
So if you're interested in embodied AI for autonomous racing and robotics, let's connect and push the boundaries of robotics together, thank you. 