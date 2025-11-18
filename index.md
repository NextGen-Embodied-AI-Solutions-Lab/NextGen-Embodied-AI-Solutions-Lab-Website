---
nav:
  order: 1
  tooltip: Home
---

# Welcome

{% include section.html %}

The NextGen-Embodied-AI-Solutions Lab conducts cutting-edge research in embodied artificial intelligence, developing innovative solutions that bridge the gap between AI systems and physical environments. Our work spans multiple domains including robotics, computer vision, natural language processing, and human-AI interaction.

## Our Team

{% include section.html %}

Our diverse team of researchers works collaboratively to advance the state-of-the-art in embodied AI systems.

{%
  include list.html
  data="members"
  component="portrait"
  filter="role == 'principal-investigator'"
  style="square"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filter="role != 'principal-investigator'"
  style="square"
%}

{%
  include button.html
  link="team"
  text="View All Team Members"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

## Our Projects

{% include section.html %}

We develop innovative projects that push the boundaries of embodied AI research.

{%
  include list.html
  data="projects"
  component="card"
  style="square"
%}

{%
  include button.html
  link="projects"
  text="View All Projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}
