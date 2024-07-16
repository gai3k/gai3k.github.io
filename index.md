---
---

# Bhat Lab Website Template

[Bhat Lab](https://github.com/greenelab/lab-website-template) uses a multipronged approach to explain the genetic, molecular and immunological basis of glioblastoma (GBM), a malignant brain cancer that is incurable.[Glioblastoma](https://www.mayoclinic.org/diseases-conditions/glioblastoma/symptoms-causes/syc-20569077)

{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%}

{% include section.html %}

## Highlights

{% capture text %}

Dr. Bhat's long-term goal is to understand GBM at the molecular and cellular levels. He uses state-of-the-art technologies and applies resulting knowledge to develop new therapeutic strategies and biomarkers for individuals with brain cancer.
{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

- Radiation resistance in glioma stemlike cells (GSCs).
- Interaction of myeloid cells, cancer cells and the central nervous system
- Developing liquid biopsies for brain cancer

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We have a multi-disciplinary team with bench scientists, immunologists, cancer biologists and bioinformaticians working in close collaboration.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
