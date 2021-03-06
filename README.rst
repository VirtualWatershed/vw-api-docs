virtualwatershed.github.io
==========================

Home for Virtual Watershed documentation.
-----------------------------------------

Welcome and thanks for visiting the GitHub home for Virtual Watershed
documentation. Below are instructions on how to contribute to the documentation. 

To learn more about all the jargon and glory of GitHub, please see these guides:

* `GitHub Flow (5 min. read) <https://guides.github.com/introduction/flow/>`_, or the general GitHub workflow
* `GitHub Hello World (10 min. read) <https://guides.github.com/activities/hello-world/>`_.  Introduction to Pull Requests, Commits, and Collaborating through GitHub
* After checking out these tutorials, you might like some of the other `GitHub guides <https://guides.github.com/>`_


Contributing
````````````

To edit the user stories you see on `http://virtualwatershed.github.io`,
click `here to edit source/index.rst <https://github.com/VirtualWatershed/virtualwatershed.github.io/edit/master/README.rst>`_.  Find your user story and make whatever
changes you like.  A user story explains three things:

1. Who
2. Wants to do what
3. Why does this person want to do this?

*How* it will be done is not included in the user story.  In the `rough draft user stories <https://virtualwatershed.github.io>`_,
I tried to say which watershed scientist was represented, what scientific things they want to do, and why these scientific things are important or why a watershed scientist would want to things as described.  One general user story for the Virtual Watershed would be something like "As a watershed scientist I want to run models through the web browser for a variety of reasons including the fact that some hydrological modeling software is outdated and difficult to install."  In our user stories, though, we want to be more specific as we already have been, for example, including which model.  When writing our user stories, we want to be as specific as possible so that we can focus our efforts.

More information on the ``.rst`` file type is below. 
Briefly, the text you see in the ``.rst``
files in the ``source/`` directory gets translated into HTML. The nice thing is,
then, that we don't actually have to write HTML, just ``.rst`` files.

When you're done, select 
"Create a new branch for this commit and start a pull request." Make up a name
that reflects the changes you've made. Don't worry about making a comment.
By doing this, the documentation maintainers know that a change has been made
and we can rebuild the documentation that users see on the website. You'll be
notified when the changes you've made are ready for viewing.

To edit other files, follow these steps:

1. Find the page you'd like to
   edit in the `source/ directory <https://github.com/VirtualWatershed/virtualwatershed.github.io/tree/master/source>`_,
2. Click on the file you want to edit.  To edit user stories, click on
   ``index.rst`` or click this `link <https://github.com/VirtualWatershed/virtualwatershed.github.io/edit/master/source/index.rst>`_.
   Then click on the pencil between the computer screen and the trash can in the
   upper-right toolbar.
3. When you've finished editing, select 
   "Create a new branch for this commit and start a pull request." Make up a name
   that reflects the changes you've made. Don't worry about making a comment. 

That will initiate a "pull request", which notifies the maintainers you've made
a change to the documentation.  They will merge your changes, rebuild the 
documentation, and you'll be notified when your changes are live on 
`http://virtualwatershed.github.io`!


Notifying the Maintainers of Issues
```````````````````````````````````

If at any point you encounter some bad information and it isn't something you
wrote (or even if it is but you don't have time to fix it yourself), create a
new "issue" about it on the `issues page <https://github.com/VirtualWatershed/virtualwatershed.github.io/issues>`_.  
By creating an issue instead of
emailing someone, we are able to see all the broken things in one place, add
more information about the issue, and track how long it's been since issues have
been raised, all to help us prioritize work.  Thanks!

Note: *this can be done for all projects that are hosted on GitHub!*


Re-Structured Text (ReST)
`````````````````````````

ReST is the "markup" format used by the excellent documentation tool 
`Sphinx <http://sphinx-doc.org/index.html>`_. 
Since it is so useful for documenting code, we are using it for
now for our documentation.  It helps us to quickly write documentation that can
be effortlessly transformed into pretty HTML for display on the web. 

You can probably figure out the syntax of ReST just by looking at the
documentation that already exists in the ``source/`` folder.

To learn more about how to write Re-Structured Text in Sphinx, navigate your 
browser `here <http://sphinx-doc.org/rest.html>`_.
