# Large Language Model-Based Virtual Robot Pick-Place Manipulation
**Large Language Model-Based Virtual Robot Pick-Place Manipulation**

While large language models possess a deep understanding of human language, translating this knowledge into effective, context-sensitive robotic actions remains a challenge. For instance, instructing a robot to ”pick an object and place it in the corner” or ”categorize these objects” should be as simple as talking to another person. This project seeks to bridge this gap, implementing a rudimentary proof of concept idea of a pick-and-place assistant in a tabletop environment. It enables a virtual robot to interpret LLM prompts and perform context-relevant actions on the various ’pick’ objects and ’place’ them appropriately. The project shall leverage LLMs, object detection, and robot manipulation.

**Note: To run the Collab notebook, you will need to have an OpenAI API key and enter the same at the beginning of the notebook.**

**Technologies Used:**
OpenCV (cv2): Computer Vision library.
CLIP: A neural network model for learning visual concepts from natural language descriptions.
Flax: A neural network library that provides a high-level API for machine learning.
JAX: A library for high-performance numerical computing that can be used for automatic differentiation and GPU/TPU acceleration.
Pybullet: A physics engine for simulating robot dynamics, designed for reinforcement learning.
Moviepy: A Python module for video editing and manipulation.
TensorFlow (compat.v1): A popular open-source machine learning framework.
Torch: A scientific computing framework used for machine learning.

**Link to Project Presentation:**
https://yuxng.github.io/Courses/CS6301Fall2023/project_group_18.pdf

**Link to Project Demo:**
https://youtu.be/Anv4h4HpFLk

**Pretrained Version:**
https://colab.research.google.com/drive/1a6Lh9un8b8IsQshRvfsCdy5u4q3Kv8QP?usp=sharing

**The version where we attempted Training:**
https://colab.research.google.com/drive/1ojv7hibcHIxumRPfE4s6poUmuPcmAg0Q?usp=sharing

**This project was an adaptation of the excellent paper and project demo linked here:**
https://say-can.github.io/

