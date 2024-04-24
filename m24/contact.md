---
layout: m24
title: Contact Us
nav_order: 10
description: >-
    Contact Information for 11671 -  Foundations of Computational Data Science Mini 5.
---

# Contact Us

<!-- If you are an incoming student or a student interested in taking the course, please email us at [Who We Are]({{ site.baseurl }}{{ page.subpath }}{% link s23/home/index.md %}#who-we-are) -->

If you are an incoming student or a student interested in taking the course, please email us at

{% assign instructors = site.staffers | where: 'role', 'Instructor' | where: 'staff_for', 'm24' | sort:"list_order" %}
<div class="staffer-container">
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

If you are currently enrolled in the course, please contact us via Piazza with your questions, concerns or feedback.

If you have any questions or feedback regarding the course or the course website, please fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSfgxVdx6DHmZ-UdezXgc-qZf4pEbe77aC-pPzYl8c9u6skOfA/viewform?usp=sf_link). 