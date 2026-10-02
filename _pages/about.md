---
layout: about
title: about
permalink: /
subtitle: Robot learning researcher · PhD candidate at Stony Brook University

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>Knowledge Systems Lab</p>
    <p>Stony Brook University</p>
    <p>Stony Brook, NY 11794</p>

selected_papers: true
social: true

announcements:
  enabled: false
  scrollable: false
  limit: 5

latest_posts:
  enabled: false
---

---

I am a Ph.D. candidate in Computer Science at [Stony Brook University](https://www.stonybrook.edu/), working in the Knowledge Systems & IRSL Lab. My research is on robot learning and autonomy: learning new skills from fewer human demonstrations, reliable navigation for mobile manipulators, and world models that predict how the physical world evolves. I work on real hardware, a Segway with a Kinova Gen3 arm and a Unitree G1 humanoid, and in simulation with Isaac Sim/Lab, MuJoCo and Gazebo.

Before my PhD, I spent several years building computer vision, NLP and deep-learning systems in industry: as a Tech Lead Engineer at Saama Technologies, at DisplaySweet in Australia, and at Kinara, where I co-invented a patented model-compression method. I received my B.Tech. and M.S. (Research) from IIT Kharagpur, where I worked on compact deep CNN models and vision-guided aerial robots that track and land on moving targets.

## Research

My goal is robots that learn new skills quickly, from a handful of demonstrations and the knowledge already inside large pretrained models, and then work reliably in the real world.

- **Teaching robots with less.** Robots shouldn't need hundreds of demonstrations. I combine PAC learning and bandit algorithms with screw-geometry motion planning, so a robot can decide which demonstration to ask for next.
- **World models for robots.** I work on world models, including joint-embedding predictive architectures (JEPA), and on diffusion policies, asking how robots can learn compact, predictive models of the world and use them to act.
- **Making big models efficient.** Large models are expensive to train and run, and that limits where robots can use them. I work on making them cheaper without losing capability, including replacing modules such as quadratic attention in pretrained transformers without destabilizing them (_Deterministic Continuous Replacement_, NeurIPS workshop 2025), and I continue to build on this.
- **Mobile manipulators and humanoids in the real world.** I build and deploy navigation and perception stacks on a Segway with a Kinova Gen3 arm and on a Unitree G1 humanoid, from SLAM to multi-sensor calibration, and test them in Isaac Sim/Lab, MuJoCo and Gazebo.

**Currently curious about:** how world models (JEPA-style and others) and large pretrained models can help robots plan and recover from failures, and what it takes to make that work on real hardware instead of only in simulation.

I also created [FaangDeck](https://faangdeck.com), a free, open resource for learning data structures and algorithms.

See my [CV](/cv/) for details, or get in touch by email.
