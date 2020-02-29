
 .. post:: Jan 18, 2020
  :tags: Docker


============================
First steps with `Docker`_
============================

.. image:: _static/docker-first-steps/docker-logo.png
    :align: center
    :scale: 30%

Here I would like to share my personal experience and the lessons I have learned since I met Docker_ for the first time.
I hope that after reading the following text, one will have basic knowledge about Docker_'s philosophy, functionality and terminology.

My first interaction with Docker was when I started on a new position as a Software developer.
Previously I had been working mostly with `LabView`_ for small projects and the atmosphere was
more like of a garage company than of a corporation (with all pros and cons that a garage company could give you of courses).
In short everything from design of the product to deployment was manually driven.

The confusion
--------------

At the new place they used Docker everywhere. They liked it so much that they
even had a `Docker Image`_ for presentations building. So was also my first task.
Imagine the situation where I, a guy who comes from a company where PowerPoint is the normal tool used for presenting,
came to a company where you need to install a Virtual Machine with Linux,
to get Docker installed on it, to run a container so as to build my presentation written in `Restructuredtext`_.
If you read these terms for the first time, probably you feel the same way as me then. Tons of questions were running through my mind:
"What does this Docker do? Why do I need it? Why I have to work one week to prepare a presentation
that can be done for a day with PowerPoint?"

Firstly, this approach seemed as a madness to me, but after few month in the company I realized the actual benefits that it provides.
Imagine a tool that will make all the presentations for the next department get together follow the same guidelines,
use the same fonts and the same corporate templates. Furthermore, every presentation will be on a web page and
can be run on every machine that have web browser and internet, but the presenter does not have to know anything about web development.
Hardly there is someone who has not experienced the bitter taste of the different PowerPoint versions and the randomly
mixed objects on the slides after opening their presentation on a different machine (apparently machine is slang for computer in software industry).

Now imagine all this is happening to all the software you develop. Yes this is possible with Docker.
If you are of this kind of people who would rather spend few hours now in order to save few weeks later, then continue.
In the next few paragraphs I am going to explain the basic thinks that I consider as an essential for Docker usage.


What is Docker
---------------
On the official Docker web page the very first description is "What is container.". Obviously it is not easy to explain in few words what the whole
Docker technology is.

Fortunately someone did the perfect explanation:

.. image:: _static/docker-first-steps/how-docker-was-born.jpg
    :align: center
    :scale: 140%

I will add also, imagine that your machine is a hero in computer game.
You can save it, send it and no matter how bad player is the one that uses when you enter the game again everything starts from that point where your save is.


Main definitions
================

------
Image
------

----------
Container
----------

Main commands
=============

--------------
Run
--------------

------
Build
------






.. _`Differential Equations`: https://ocw.mit.edu/courses/mathematics/18-03sc-differential-equations-fall-2011/index.htm
.. _`Probabilistic Systems Analysis and Applied Probability`: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013/index.htm
.. _`Design and Analysis of Algorithms`: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-design-and-analysis-of-algorithms-spring-2015/index.htm
.. _`Principles of Microeconomics`: https://ocw.mit.edu/courses/economics/14-01sc-principles-of-microeconomics-fall-2011/index.htm
.. _`LabView`: https://www.ni.com/en-rs/shop/labview.html
.. _`Docker`: https://www.docker.com/
