---
title: AI Project
role: Software Programmer
image: assets/image-sample.png
alt: AI Project
tools: C++ | C# (Unity)
asset-base: /assets/programming/ai/
tags: ai

caption:
  title: AI Project
  subtitle: Path Finding <br> Steering Behavior
  thumbnail: /assets/programming/ai/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/REPLACE-WITH-CODE
  detail:
    - title: Path Finding
      desc: Find a smooth path with A star search algorithm and analysis the terrain to detect and seek the player. There are four types of heuristic function. The user can change the map or heuristic function or apply smoothing or rubberbanding to the path.
    - title: Steering Behavior
      desc: Implement steering behavior; seeking and obstacle avoidance. An autonomous character that avoids obstacles and moves towards the item.

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
---

<hr/>
{% include custom/gallery title="Path Finding" id="images_astar" desc="This is A star pathfinding" %}