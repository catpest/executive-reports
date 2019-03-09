---
layout : default
title : Analysis
---
<table>
<thead>
<tr class="header">
<th>Month</th>
<th>Week</th>
<th>Date</th>
<th>Category</th>
<th>Account</th>
<th>Description</th>
<th>Amount</th>
</tr>
</thead>
<tbody>
{% for item in site.data.analysis %}
<tr>
<td markdown="span">{{item.month}}</td>
<td markdown="span">{{item.week}}</td>
<td markdown="span">{{item.date}}</td>
<td markdown="span">{{item.category}}</td>
<td markdown="span">{{item.account}}</td>
<td markdown="span">{{item.description}}</td>
<td markdown="span">{{item.amount}}</td>
</tr>
{% endfor %}
</tbody>
</table>

