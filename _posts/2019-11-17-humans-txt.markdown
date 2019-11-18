---
layout: post
title: humans.txt, robots.txt
date: 2019-11-17
---

* **What is robots.txt and how have you configure it for your site?**

robots.txt is a text file with UTF-8 encoding and functions with the protocols *http*, *https* and *FTP*.
The file should be located in the root catalogue (together with humans.txt, package.json).

This file is created in order to control which files are allowed/disallowed to be scanned by bots of the searching engines. My robots.txt file looks like:

~~~
User-agent: *
Disallow: /_site/about/
Disallow: /*.jpg
~~~~

It means that it concerns all the searching robots (google, yandex, googlebot-image, googlebot-mobile, etc) and that "about" page and all the .jpg pictures are not available for searching robots.

* **What is humans.txt and how have you configure it for your site?**

The idea with the file humans.txt is to acquaint the users with the developers, designers, copywriters, SEO specialists, webmaster, etc. It can also prove the authorship of the site.
The case is important here, so the file should have the name "humans.txt" and not Humans.txt or HUMANS.txt. The file should be located in the root (together with robots.txt, package.json and folders with site files)
This is how i configured the file:

~~~~
/ * TEAM */
        Student: Mariia Roze
        Email: roze2117@gmail.com
        GitHub: mariamira
        
/ * THANKS */
        Teacher: Johan Leitet
        Email: johan.leitet@lnu.se
        Twitter: @leitet
        
/ * SITE */
        Last update: 2019/11/16
        Language: English
        IDE: Visual Studio Code, Komodo Edit
~~~~

Thus I mentioned myself, course teacher and some info about the site creation. 
It is possible to add the file to the head of the website, but I decided not to do it.