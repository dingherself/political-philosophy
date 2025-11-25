---
layout: toc
title: Syllabus
navtitle: Syllabus
group: syllabus
order: 5
date: 2025-11-25
---

<h2 class="mt-0" style="position:absolute; visibility: hidden;">Course Information</h2>

<p class="mt-2"><strong>{{ site.course_number }}: {{ site.course_title_full | smartify }}</strong><br />
{{ site.institution | smartify }}, {{ site.semester | smartify }}<br />
{{ site.meeting_time }}, {{ site.classroom | smartify }}, <a href="{{ site.learning_site }}">CourseWorks</a></p>

<script language="JavaScript" type="text/javascript">
      var g = "edu";
      var o = "barnard";
      var c = ".";
      var a = "dding";
      var t = " ";
      var s = "@";
      document.write("<p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}' target='_blank'>{{ site.instructor | smartify }}</a> (my pronouns are <a href='https://apastyle.apa.org/blog/singular-they' target='_blank' rel='noopener noreferrer'>they/them</a> and she/her)<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + a + s + o + c + g + "'>" + a + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br />" + "</p>");
</script>
<noscript><p><strong>Instructor</strong>: <a href='{{ site.instructor_website }}' target='_blank'>{{ site.instructor | smartify }}</a> (my pronouns are <a href='https://apastyle.apa.org/blog/singular-they' target='_blank' rel='noopener noreferrer'>they/them</a> and she/her)<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.office }}<br /><strong>Office hours</strong>: {{ site.office_hours }}<br /></p></noscript>

{% if site.ta_title %}

<div class="row no-gutters gx-0 mb-0">
      <div class="col-12">
      <script language="JavaScript" type="text/javascript">
            var g = "edu";
            var o = "columbia";
            var c = ".";
            var i = "{{ site.ta1_netid }}";
            var t = " ";
            var s = "@";
            document.write("<p><strong>{{ site.ta_title }}:</strong>: {{ site.ta1_name | smartify }}<br /><strong>Email</strong>:" + t + "<a href='" + "mail" + "to:" + i + s + o + c + g + "'>" + i + s + o + c + g + "</a><br /><strong>Office</strong>: {{ site.ta1_office }}<br /><strong>Office hours</strong>: {{ site.ta1_office_hours }}<br />" + "</p>");
      </script>
      <noscript><p><strong>{{ site.ta_title }}</strong>: {{ site.ta1_name | smartify }}<br /><strong>Email</strong>:[you must enable JavaScript in your web browser to view the email address]<br /><strong>Office</strong>: {{ site.ta1_office }}<br /><strong>Office hours</strong>: {{ site.ta1_office_hours }}<br /></p></noscript>
      </div>

</div>

{% endif %}

## Course Description

How should we live together? This course considers and critiques received answers to this question from the history of Western philosophy. We will spend the first half of the semester working our way through the development of modern political philosophy as a field. We will then take a deep dive into the political critiques that emerged from the civil rights, anti-war, women’s liberation, and gay rights movements of the 1960s, which are being rediscovered and recentered in political philosophy today.

## [Schedule]({{ site.baseurl }}{% link schedule.html %})

## [Course Policies]({{ site.baseurl }}{% link course-policies.md %})

[under construction]