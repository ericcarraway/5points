---
layout: page
title: Staff
---
<style>
.staff-nav {
    max-width: 108px;
    max-height: 108px;
    display: inline-table;
}
.staff-nav p {
    color: #333333;
    font-size: 10px;
    margin: 1px;
    padding: 1px;
}
.staff-nav img {
    margin: 2px;
    padding: 2px;
    border-radius: 6px;
}
h6 {
    color: #111111;
    font-size: 13px;
    margin: 1px;
    padding-bottom: 18px;
}
</style>
<!-- for staff_member in site.data.staff -->
{% for staff_member in site.data.staff %}
<a href="../../staff/{{ staff_member.kebab_case }}">
  <div class="col span_3 center staff-nav">
    <img class="{{ staff_member.kebab_case }}-small" src="../../public/staff-headshots/bw/{{ staff_member.kebab_case }}.jpg" alt="{{ staff_member.title_case }}">
    <h6>{{ staff_member.title_case }}</h6>
  </div>
</a>
{% endfor %}
<!-- endfor -->
<div class="col span_12">
<br>
<h6>Aaron Barnes: Visual Instructor</h6>
<h6>Courtney Kirkwood: Director of Operations</h6>
<h6>Svenja Fuhrig: Business Manager</h6>
<h6>Adam Chitta: Administrative Assistant</h6>
</div>
