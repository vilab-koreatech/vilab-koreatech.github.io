---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

의료와 제조 산업에서의 다양한 인공지능 연구에 대해 관심이 있는 학생들은 언제든 연락주세요.   
학부연구생 및 석사과정 학생을 모집합니다.

{%
  include button.html
  type="email"
  text="haeyun@koreatech.ac.kr"
  link="haeyun@koreatech.ac.kr"
%}
{%
  include button.html
  type="phone"
  text="(+82)-41-560-1644"
  link="+82-41-560-1644"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/4gwKHp3ye5BQ93MR9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

<div style="width:100%; height:auto; max-width:600px; margin:0 auto;">
  <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d3196.198735369992!2d127.2823652!3d36.7657996!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357b2ac473ccb835%3A0x153e00c065b63f28!2z7ZWc6rWt6riw7Iig6rWQ7Jyh64yA7ZWZ6rWQIOqzte2VmTLqtIA!5e0!3m2!1sko!2skr!4v1731901590271!5m2!1sko!2skr" 
    width="100%" 
    height="400" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>
</div>

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

