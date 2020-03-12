---
title: 'Computer Friday: New attempt at version control meeting '
author: Erik Ø. Sørensen
date: '2020-03-11'
slug: new-attempt-at-version-control-meeting
categories: []
tags: []
---

**CANCELLED BECAUSE OF CORONA VIRUS CONCERNS!**
Last Friday we had some technical issues. We won't let that hold us back, and there will be a new 
attempt on Friday March 13 -- in FAIR-1. The topic of the day
will be **version control**, in particular the subversion system that Choice Lab researchers
have been using since 2007. 

From the manual for subversion: 

> Subversion is a free/open source version control system (VCS). That is, Subversion manages files and directories, and the changes made to them, over time. This allows you to recover older versions of your data, or examine the history of how your data changed. In this regard, many people think of a version control system as a sort of “time machine.”

> Subversion can operate across networks, which allows it to be used by people on different computers. At some level, the ability for various people to modify and manage the same set of data from their respective locations fosters collaboration. Progress can occur more quickly without a single conduit through which all modifications must occur. And because the work is versioned, you need not fear that quality is the trade-off for losing that conduit—if some incorrect change is made to the data, just undo that change.

> http://svnbook.red-bean.com/en/1.7/svn.intro.whatis.html


In addition to providing an overview of how subversion works, I'll try to provide
a comparison to "Git", which might be a more popular system today (but also more complex). 
I'll also show how one particular piece of FAIR infrastructure, our joint bibliography database "mmbib",
is available as a subversion "repository". 

All participants will get a personal subversion repository, and explanations for how to establish
collaborative repositories to hold research project content.


# Before the meeting
If you want to join the practice session, you need to have a subversion client installed
on your computer. If you have a windows computer, the client you want is most likely 
[Tortoise SVN](https://tortoisesvn.net/). If you don't have administrative rights, 
you probably need to ask IT services for help installing it. 
If you have a mac there are many choices -- a fully
graphical interface is [Versions](https://versionsapp.com/), but it is also possible to use
a terminal client (Ceren might be the one with the most experience on this).