---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

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

<h2>Conference and Journal Articles</h2>

<table style="width:100%" cellpadding="0" border="0">
{% for paper in site.data.publications %}
  <tr><td width="120" valign="top">{{ paper.venueshort }}</td>
  <td><strong>{{ paper.title }}</strong>. {{ paper.authors }} <em>{{ paper.venue }}. {{ paper.issue }}</em><br>
  <a href="{{ paper.paperurl }}">PDF</a> | <a href="{{ paper.doi }}">DOI</a></td></tr>
{% endfor %}

</table>

<h2>Other Publications</h2>

<table style="width:100%" cellpadding="0" border="0">
{% for paper in site.data.otherpublications %}
  <tr><td width="120" valign="top">{{ paper.venueshort }}</td>
  <td><strong>{{ paper.title }}</strong>. {{ paper.authors }} <em>{{ paper.venue }}. {{ paper.issue }}</em><br>
  <a href="{{ paper.paperurl }}">PDF</a> | <a href="{{ paper.doi }}">DOI</a></td></tr>
{% endfor %}

</table>