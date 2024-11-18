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

<div style="width:100%; height:400px;">
  <iframe 
    src="https://map.naver.com/v5/?c=14127809.6506319,4516065.6143352,15,0,0,0,dh" 
    width="100%" 
    height="400" 
    frameborder="0" 
    allowfullscreen="">
  </iframe>
</div>

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

