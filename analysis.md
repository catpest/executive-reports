---
layout : default
title : Analysis
---
<table>
<colgroup>
<col width="30%" />
<col width="70%" />
</colgroup>
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

| Month | Week | Date | Category | Account | Description | Amount |
|---------|---------|---------|---------|---------|---------|---------|
{% for item in site.data.analysis %}
| {{item.month}} | {{item.week}} | {{item.date}} | {{item.category}} | {{item.account}} | {{item.description}} | {{item.amount}} |
{% endfor %}
