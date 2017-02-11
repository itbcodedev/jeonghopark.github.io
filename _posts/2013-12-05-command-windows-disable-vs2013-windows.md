---
layout: post
title: command windows disable (VS2013, Windows)
date: 2013-12-05 16:50:14.000000000 +01:00
categories:
- code
- openframeworks
tags:
- openframeworks
- vs2013
status: publish
type: post
published: true
author:     "jeonghopark"
header-img: ""
comments: true

---
command windows disable


<p>in main.cpp</p>



<p><pre><code>#pragma comment(linker, "/SUBSYSTEM:windows /ENTRY:mainCRTStartup")</code></pre></p>
