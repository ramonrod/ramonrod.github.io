---
layout: post
title: "Processing"
date: 2013-01-03 15:00:00
categories: Programming
tags: post
image:
---

http://processing.org/

“Processing is an open source programming language and environment for people who want to create images, animations, and interactions. Initially developed to serve as a software sketchbook and to teach fundamentals of computer programming within a visual context, Processing also has evolved into a tool for generating finished professional work. Today, there are tens of thousands of students, artists, designers, researchers, and hobbyists who use Processing for learning, prototyping, and production.”

I think Processing it is a really powerful tool for graphic representations. Here is one example which you also can find on the Processing website: Download and start the java-application below by double clicking on it. Move the mouse across the pop-up window interface. If you press the mouse button within the windows interface the circles will turn black. You can fine many others examples in the tutorials of Processing. Have fun!

Try it yourself is fun!

1. Download processing.

2.Create a file in an editor called: "draw_circles.jar", or whatever you want. The file format ".jar" referes to a "java archive" file.

3. Write the following code in the file and save it:
{% highlight java %}
void setup() {  
size(480, 480);} 
void draw() {  
if (mousePressed)  
{fill(0);}
{% endhighlight %}

3. Dobble click on the file, and woila ... start playing with it. A window will appear where you can move and click the cursor of mouse across it, and see what happends!
