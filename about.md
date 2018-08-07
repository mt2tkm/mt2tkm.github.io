---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

<font size="5">松本 拓海</font>
<br>
大阪大学大学院 情報科学研究科 修士課程1年 <br>
<a href="http://www-bigdata.ist.osaka-u.ac.jp/ja/home/">鬼塚研究室</a>
<br>

---

## Awards
<ul>
{% for award in site.data.awards %}
  <li>
      <strong> {{ award.award }} </strong> <br>
	  {% for member in award.author %}
	  		{{member}}　
	  {% endfor %} <br>
	  {{ award.from }} ({{ award.day }})
  </li>
{% endfor %}
</ul>

---

## Publications
<ul>
{% for paper in site.data.paper %}
  <li>
      <strong> {{ paper.title }} </strong> <br>
	  {% for member in paper.author %}
	  		{{member}}　
	  {% endfor %} <br>
	  {{ paper.conference }} ({{ paper.day }})
  </li>
{% endfor %}
</ul>

---

## Skills
<ul class="skill-list">
	<li>Git</li>
	<li>Python</li>
	<li>Scala</li>
	<li>C++</li>
	<li>MySQL - MongoDB</li>
</ul>

## Projects
<ul>
	<li><a href="https://github.com/OnizukaLab/CoRIN">OnizukaLab/CoRIN</a></li>
</ul>

---

## History
- 1996.03 : 大阪府生まれ
- 2014.04 : 大阪大学 工学部電子情報工学科 入学
- 2016.10 : 鬼塚研究室　配属
- 2018.03 : 大阪大学 工学部電子情報工学科 卒業
- 2018.04 : 大阪大学大学院 情報科学研究科マルチメディア工学専攻 入学
