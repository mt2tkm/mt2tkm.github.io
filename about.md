---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

<font size="5">松本 拓海 / Takumi Matsumoto</font>
<br>
大阪大学大学院 情報科学研究科 修士課程 1年 <br>
<a href="http://www-bigdata.ist.osaka-u.ac.jp/ja/home/">鬼塚研究室</a>
<br>

---

## <span style="border-bottom: solid 5px red">Awards</span>
<ul>
{% for award in site.data.awards %}
  <li>
      <strong> {{ award.award }} </strong> <br>
	  {% for member in award.author %}
        {% if member == "鬼塚 真" || member == "Makoto Onizuka" %}
            {{member}}．
        {% else %}
            {{member}}，
        {% endif %}
	  {% endfor %} <br>
	  {{ award.from }} ({{ award.day }})
    {% if award.link != "" %}
      {{award.link}}
    {% endif %}
  </li>
{% endfor %}
</ul>

---

## <span style="border-bottom: solid 5px red">Publications</span>

<ul>
{% for paper in site.data.paper %}
  <li>
      <strong> {{ paper.title }} </strong> <br>
	  {% for member in paper.author %}
	  		{% if member == "鬼塚 真" || member == "Makoto Onizuka" %}
            {{member}}．
        {% else %}
            {{member}}，
        {% endif %}
	  {% endfor %} <br>
	  {{ paper.conference }} ({{ paper.day }})
  </li>
{% endfor %}
</ul>

---

## <span style="border-bottom: solid 5px red">Skills</span>
<ul class="skill-list">
	<li>Git</li>
	<li>Python</li>
	<li>Scala</li>
	<li>C/C#/C++</li>
  <li>Ruby</li>
	<li>MySQL - MongoDB</li>
  <li>GCP/AWS</li>
</ul>

## <span style="border-bottom: solid 5px red">Projects</span>
<ul>
	<li><a href="https://github.com/OnizukaLab/CoRIN">OnizukaLab/CoRIN</a></li>
</ul>

---

## <span style="border-bottom: solid 5px red">History</span>
- 1996.03 : 大阪府生まれ
- 2014.04 : 大阪大学 工学部電子情報工学科 入学
- 2016.10 : 鬼塚研究室　配属
- 2018.03 : 大阪大学 工学部電子情報工学科 卒業
- 2018.04 : 大阪大学大学院 情報科学研究科マルチメディア工学専攻 入学
