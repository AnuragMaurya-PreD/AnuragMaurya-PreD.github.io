---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Research Thoughts I want to further explore
===
* Exploring Multimodal Approaches for Imitation: Using Multimodal Data: The idea of using multimodal approaches in imitation learning involves amalgamating various data types like images, text, audio, and sensor inputs to teach models how to mimic human behaviors. By extracting features from different modalities, and combining them into a unified representation. The real question is what modality is sufficient and how to make a good approximation. I wish to extend my previous work on Video-based action recognition to extend to other sensor data like Joint angles or multiple views of the environment.
* Using Play data to its fullest potential(Do we need experts?) I recently did a seminar course on Intelligent Robotic Manipulation and was assigned to present a paper “Learning Latent Plans from Play” on using Play Data for training a Goal Conditioned Behaviour cloning approach. Intriguingly, We might not need expensive supervised labeled data at all for training. Randomization has its beauty magnified in the intrinsics of Play Data. This opens a plethora of approaches that can be used to solve problems too complex to model but might be easier to explore using play. 
* One direct application can be solving a complex puzzle or mimicking an origami task to generate different structures in reinforcement learning. Using Imitation in Soft Robotics can be a game changer in my opinion.
* Using Classical Logic to Take Reinforcement Learning Beyond
Using classical logic to extend reinforcement learning involves integrating logical reasoning and symbolic representation into the learning process. I want to explore how structuring data neurosymbolically can simplify complex function approximations. During my internship at TU Darmstadt, I learned how changing the format of the input data can make methods and models more efficient and easy to explain.

I am also interested in:
===
* Simultaneous localization and Mapping: I am particularly interested in 2.5D navigation.
* Model-based Reinforcement Learning: Haven’t worked on an appliaction in the field but will want to explore for sure