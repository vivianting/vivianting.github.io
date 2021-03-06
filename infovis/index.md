---
layout: archive
title: "可视化作品集"
date: 2018-1-7T15:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature:
  teaser:
  
---
<style>
h4{background: #ff4d4d; color:white; border-radius:6px; padding:6px;}
h5{background: #1a8dff; color:white; border-radius:3px; padding:3px;}
</style>

<h4>五大药房在中国的分布情况</h4>
大参林_国大药房_老百姓_同仁堂_一心堂 *[点击此处可跳至本作品的Tableau Public](https://public.tableau.com/profile/.1847#!/vizhome/_18112/1?publish=yes)

此研究根据高德地图搜索结果得出<b>4271笔</b>数据

<div class="row">
<div class="col-sm-4" markdown="1"><!-- left -->
##### 总数比较：五大药房在中国的分布总数相差不大
最少的是同仁堂，有825所；
最多的是国大药房，有875所。
![总数比较](https://vivianting.github.io/images/pharmacy_2.png)

##### 盒须图：五大药房地理分布差异比较
- 大参林、一心堂分布的集中性明显。
- 大参林在广东省的分布数最大，经搜索得知广东省为其发源地
- 一心堂在云南省的分部数最大，经搜索得知云南省是其发源地 
![盒须图](https://vivianting.github.io/images/pharmacy_box.png)

</div>


<div class="col-sm-4" markdown="1" ><!-- center -->
##### 地图：五大药房的地理分布情况
![地图](https://vivianting.github.io/images/pharmacy_map.png)
- 大参林、一心堂的分布显示为集中性。大参林主要分布在两广地区，一心堂大多分布在我国西南部，在云南省最为集中
- 老百姓、同仁堂的分布范围较广，在新疆、甘肃也有分布
- 同仁堂主要分布在中部和东部地区
- 国大药房的分布也体现出了聚集分布的特征，体现为在各个省份的某一块区域的聚集分布

  
##### 各省比较：五大药房在各省的数量分布及比对
- 大参林在广东省的分布最多，一心堂在云南省的分布最多
- 同仁堂的分布范围最广，在有数据的所有省分中都有分布，次之为老百姓
![各省比较](https://vivianting.github.io/images/pharmacy_1.png)
</div> 


<div class="col-sm-4" markdown="1" ><!-- right -->
##### 各省：各省的药房分布数量之五大药房

![各省](https://vivianting.github.io/images/pharmacy_chart.png)

- 广东省的药房分布总数最多，且五大药房都有分布；
- 西藏和台湾没有数据，可能是没有分布或未录入高德地图
- 在有数据的省份中，澳门最少
- 药房的分布数与经济、人口、对药品的关注程度有关
   - 广东省的经济发达、人口众多，药房分布数最大
   - 云南省虽经济不在发达省份行列，但其对药品的重视程度较高，因而药房数量较多

</div>
 
<hr>
<br/>

以下展示其它作品

<div class="tiles">
{% for post in site.categories.posts infovis %}
  {% include post-grid.html %}
{% endfor %}
</div>