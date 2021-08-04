---
layout: cover
---
# Welcome to my Project Portfolio

---
layout: section
---
# Projects I've Made

---
---
# ax-toolkit
This is a set of scripts designed for making Axelor easier to use and deploy.

It currently includes:
- ax-get.py

  A Python script which makes it easy to download Axelor in both compiled-WAR form and in source form.
- ax-inconv.py

  A Python script which takes a list of inventory items (currently only support Excel files as input) and outputs a CSV file that can be imported into Axelor.

---
---
# genscripts
This is a set of scripts for use with Gentoo servers. Contributions are always welcome.

It currently includes:
- gensync.sh
  
  A shell script to ensure that '''emerge --sync''' hasn't been run more than once in a day.

- genwork.sh
  
  Adds a file warning other scripts not to do anything to disruptive, as some serious work is going on.

- genoff.sh
  
  A wrapper to '''poweroff''' that waits until any genwork files have been removed before shutting down the computer.

---
---
# add
This is one of the first programs I've ever made. Currently only adds two floats together. More features are added only on request.

---
---
# divisus
A Python script for converting columns of text into a CSV file. This script can be considered as the first attempt at an inventory conversion solution for Axelor before _ax-inconv.py_ was created.

---
---
# strcrop
A simple C program that crops user-provided strings. Aims to be a string cropping library someday.

---
layout: section
---
# Projects I've Forked
(And made changes to)

---
---
# Speckpater
A Python platformer game where a Priest collects Bibles in a dangerous Jungle. Major improvements are ongoing.

---
---
# tomcat-rpm-spec
Provides scripts and an RPM spec file to easily generate an updated RPM package for _Apache Tomcat_.

---
title: The End
layout: end
---
