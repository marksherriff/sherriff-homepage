---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

_Currently Under Construction - Transferring from Old Website_

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


<div class="bibliography" reversed="reversed"><span><style>
table, th, td {
  border: 0px;
  border-collapse: collapse;
}
</style>
<table style="width:100%" cellpadding="0" border="0">
{% for paper in site.data.publications %}
  <tr><td width="120" valign="top">{{ paper.venueshort }}</td>
  <td><div class="reference">{{ paper.title }}</div></td></tr>
{% endfor %}

</table>
