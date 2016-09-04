---
layout: post
title: First Commit
description: "Its ON, baby"
headline: "Let's Fire up the Engines"
categories: personal
tags: 
  - jdk
  - version
  - java
  - ubuntu
  - 16.04
  - update
imagefeature: "website-speed.jpg"
imagecredit: spreadeffect.com
imagecreditlink: "http://www.spreadeffect.com/blog/improve-website-speed/"
comments: false
mathjax: null
featured: true
published: true
---
<b><h1>Oracle JDK 8</h1></b><br>
This is the latest stable version of Java at time of writing, and the recommended version to install. You can do so using the following command:<br>
	<code>sudo apt-get install oracle-java8-installer</code>
<b><h1>Managing Java</h1></b><br>
There can be multiple Java installations on one computer . You can configure which version is the default for use in the command line by using update-alternatives, which manages symlinks used for different commands.<br>
<code>sudo update-alternatives --config java</code>
<br>
after running this command you will have a screen similar to this
<pre><code>
There are 5 choices for the alternative java (providing /usr/bin/java).
Selection    Path                                            Priority   Status
  0            /usr/lib/jvm/java-8-oracle/jre/bin/java          1084      auto mode
  1            /usr/lib/java/jdk1.8.0_102/bin/java              1         manual mode
  2            /usr/lib/jvm/java-7-oracle/jre/bin/java          1082      manual mode
  3            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      manual mode
  4            /usr/lib/jvm/java-8-oracle/jre/bin/java          1084      manual mode
* 5            /usr/lib/jvm/jdk1.8.0_102/jre/bin/java           180       manual mode

Press <enter> to keep the current choice[*], or type selection number: 
</code>
</pre>
Do the same thing for javac and select the appropriate choice.