# OpenAI "Robots that learn": one-shot imitation from a VR demonstration

- **Date:** 2017-05-16
- **Who:** OpenAI (Peter Welinder, Bob McGrew, Jonas Schneider, Jonathan Ho, Marcin Andrychowicz, Pieter Abbeel, Ilya Sutskever and others)
- **Type:** research

OpenAI's blog post described a robot system trained entirely in simulation that can learn a new task after seeing one demonstration. A person shows the task in VR, and the robot then performs it from an arbitrary starting configuration. The vision network was trained on simulated images with domain randomization, and the imitation network learns from the single demonstration. It applied the one-shot imitation learning method from the March 2017 arXiv paper to a physical robot.

## Sources
- https://openai.com/blog/robots-that-learn/
- https://engadget.com/2017/05/16/openai-s-new-system-lets-you-train-robots-entirely-in-vr
