---
---

# 实验室模板网站

这里是未来人工智能创新实验室, 目前我们在招AI实习研究生,欢迎你的加入!

{% include section.html %}

## Highlights

{% capture text %}

我们的研究集中在计算机视觉，三维重建,具体来说我们主要利用NerF算法来实现3D物体的高保真建模渲染.

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

我们目前正在开发一个大型的Text-3D Model的 人工智能生成式平台.

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

我们的公司包的员工来自985/211高校,国内大型互联网企业, 同时还一大量海外留学背景的工程师加入.

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
