---
---

# vilab-koreatech's Website

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## News

{% capture text %}

VILAB에서 학부연구생을 모집하니, PUBLICATIONS나 RESEARCH에서 관심 분야가 있다면 메일로 연락주시거나 직접 찾아와주세요.

{%
  include button.html
  link="contact"
  text="Contact"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="학부연구생/석사과정 모집합니다."
  text=text
%}

{% capture text %}

Kyungsu Lee, Haeyun Lee, Juhum Park, Jae Youn Hwang, "Fine-Grained Binary Object Segmentation in Remote Sensing Imagery via Path-Selective Test-Time Adaptation", IEEE Transactions on Geoscience and Remote Sensing

{%
  include button.html
  link="research"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="paper_img/TGRS_2024.png"
  link="research"
  title="Our paper accepted to IEEE Transactions on Geoscience and Remote Sensing."
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
