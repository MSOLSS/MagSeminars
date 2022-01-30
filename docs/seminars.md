---
title: Past Speakers
layout: "page"
icon: fa-user-astronaut
order: 4
---

Schedule by year: <a href="#2021">2021</a>, <a href="#2020">2020</a>. 

<h2><a id="2021">2021</a></h2>

<div style="height:100%; width:90%; overflow:auto;">

<table>
<thead>
<th>Date</th>
<th>Speaker</th>
<th>Seminar</th>
<th>Institution</th>
</thead>
<tbody>

{% assign file = site.data.2021 %}

{% for row in file %}
  <tr>
  <td> {{ row.date }} </td>
  <td> {{ row.speaker }} </td>
  <td> <a href="{{row.link}}"> {{ row.title }} </a> </td>
  <td> {{ row.institution }} </td>
  </tr>
{% endfor %}
</tbody>
</table>

</div>

<h2><a id="2020">2020</a></h2>

<div style="height:100%; width:90%; overflow:auto;">

<table>
<thead>
<th>Date</th>
<th>Speaker</th>
<th>Seminar</th>
<th>Institution</th>
</thead>
<tbody>

{% assign file = site.data.2020 %}

{% for row in file %}
  <tr>
  <td> {{ row.date }} </td>
  <td> {{ row.speaker }} </td>
  <td> <a href="{{row.link}}"> {{ row.title }} </a> </td>
  <td> {{ row.institution }} </td>
  </tr>
{% endfor %}
</tbody>
</table>

</div>