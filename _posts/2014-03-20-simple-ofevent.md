---
layout: post
title: simple ofEvent
date: 2014-03-20 16:17:13.000000000 +01:00
categories:
- code
- memo
- openframeworks
tags:
- openframeworks
status: publish
type: post
published: true
author:     "jeonghopark"
header-img: ""
comments: true
---

ofEvent Code



{% highlight c++ %}    
//-.h
ofEvent<"anything"> "<strong>name</strong>";
void "name function"();

//-.cpp
ofAddListener( "ofEvent __name", this, &ofApp::"name function");
ofNotifyEvent( "ofEvent __name", Value );
void "name function"() {
    "make somthing";
}
{% endhighlight %}    
