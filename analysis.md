---
layout : default
title : Analysis
---

| Month | Week | Date | Category | Account | Description | Amount |
|---------|---------|---------|---------|---------|---------|---------|
{% for item in site.data.analysis %}
| {{item.month}} | {{item.week}} | {{item.date}} | {{item.category}} | {{item.account}} | {{item.description}} | {{item.amount}} |
{% endfor %}
