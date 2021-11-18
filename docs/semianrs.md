---
title: Speakers and Seminars
layout: "page"
icon: fa-calendar-altfa-user-astronaut
order: 3
---

Seminars are held every Monday at 1200 EDST (1600 UT) unless otherwise stated below.

Schedule by year: <a href="#2021">2021</a>, <a href="#2020">2020</a>. 

<h2><a id="2021">2021</a></h2>

<div class="display compact" style="height:100%; width:90%; font-size:	16px; overflow:auto;">

<table id="catalogue" class="display">
<thead>
<tr class="header">
<th style="font-size: 16px" data-sort>Date</th>
<th style="font-size: 16px">Speaker</th>
<th style="font-size: 16px">Seminar</th>
<th style="font-size: 16px">Institution</th>

</tr>
</thead>
<tbody>

{% assign file = site.data.2021 %}

{% for row in file %}
  <tr>
  <td> {{ row.date }} </td>
  <td> {{ row.speaker }}</td>
  <td> {{ row.title }} </td>
  <td> {{ row.institution }} </td>
  </tr>
{% endfor %}
</tbody>
</table>

</div>