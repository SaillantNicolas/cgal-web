---
layout: post
title: "Header-Only CGAL"
description: "Remove the need to build a CGAL library"
category:
tags: ["WIP"]
---
{% include JB/setup %}

<h3>Guillaume Damiand, and Clement Jamin</h3>
<h4>Liris, Lyon</h4>

<p>When you install CGAL, you typically build 4 libraries: CGAL itself, Algebraic numbers, Qt, and ImageIO.
As CGAL uses C++ templates, these libraries are rather empty, and we are working towards making them obsolete.</p>

<p><b>Status:</b> Submitted to the Editorial Board and targeted for CGAL 4.7, Autumn 2015</p>