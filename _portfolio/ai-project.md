---
title: AI Project
role: Software Programmer
image: assets/image-sample.png
alt: AI Project
categories: C++ Unity C#
asset-base: /assets/programming/ai/
tags: ai

priority : 9

caption:
  title: AI Project
  subtitle: Path Finding <br> Steering Behavior
  thumbnail: /assets/programming/ai/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/07GFqc1JByI
  detail:
    title: AI projects
    desc: Pathfinding & Steering Behavior

images_astar:
  - image-path: path-astar.png
    alt: A star algorithm
    desc: A star algorithm
  - image-path: path-smoothing.png
    alt: smoothing the path
    desc: smoothing the path
  - image-path: path-rubberbanding.png
    alt: merge the path
    desc: merge the path

images_sb:
  - image-path: seeking.png
    alt: seeking
    desc: seeking
  - image-path: obstacle-avoidance.png
    alt: obstacle avoidance
    desc: obstacle avoidance
---

<hr/>
{% include custom/section-header title="Pathfinding" %}
{% include custom/gallery id="images_astar" %}
Find a smooth path with A star search algorithm and analysis the terrain to detect and seek the player. There are four types of heuristic function. The user can change the map or heuristic function or apply smoothing or rubberbanding to the path.

{% include custom/section-header title="Steering Behavior" %}
{% include custom/gallery id="images_sb" %}
Implement steering behavior; seeking and obstacle avoidance. An autonomous character that avoids obstacles and moves towards the item.