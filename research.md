---
title: Research
layout: page
---
# 研究関連

## <span style="border-bottom: solid 5px red">Reserch Interest</span>
- 探索的データ分析 (Explanatory Data Analysis)
- データマイニング
- データベース
- OLAP (Online Analytical Processing)
- 異常検知 (Outlier Detection)
- データキューブ

## <span style="border-bottom: solid 5px red">Internship</span>
1. （株）三菱電機
  - 期間：一か月 (2017.08 - 2017.09)
  - 情報技術総合研究所

2. （株）リクルート
  - 期間：一か月 (2018.09)

3. （株）CyberAgent
  - 期間：2days
  - データコンペティション
  - 結果：1位

## <span style="border-bottom: solid 5px red">Publications</span>

### 主著論文
<ul>
{% for paper in site.data.paper %}
  <li>
      <strong> {{ paper.title }} </strong> <br>
	  {% for member in paper.author %}
	  		{% if member == "鬼塚 真" %}
            {{member}}．
        {% else %}
            {{member}}，
        {% endif %}
	  {% endfor %} <br>
	  {{ paper.conference }} ({{ paper.day }})
  </li>
{% endfor %}
</ul>

### その他
<ul>
{% for paper in site.data.paper_sub %}
  <li>
      <strong> {{ paper.title }} </strong> <br>
	  {% for member in paper.author %}
	  		{% if member == "鬼塚 真" %}
            {{member}}．
        {% else %}
            {{member}}，
        {% endif %}
	  {% endfor %} <br>
	  {{ paper.conference }} ({{ paper.day }})
  </li>
{% endfor %}
</ul>