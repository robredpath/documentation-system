.. _how-to:

How-to guides
=============

..  rubric:: How-to guides are **directions** that take the reader through the steps required to solve a real-world
    problem. How-to guides are **goal-oriented**.

===========

How-to guides are recipes, directions to achieve a specific end - for example: *how to create a web form*; *how to plot a three-dimensional data-set*; *how to enable LDAP authentication*.

.. image:: /images/overview-how-to.png
   :alt: 'How-to guides - task oriented, practical steps, that serve our work'
   :align: right
   :width: 50%

**How-to guides are wholly distinct from tutorials** and must not be confused with them:

* A tutorial is what you decide a beginner needs to know.
* A how-to guide is an answer to a question that only a user with some experience could even formulate.

In a how-to guide, you can assume some knowledge and understanding. You can assume that the user already knows how to do basic things and use basic tools.

Unlike tutorials, how-to guides in software documentation tend to be done fairly well. They’re also fun and easy to write.

================

Analogy from cooking
--------------------

.. image:: /images/recipe.jpg
   :alt: 'a recipe'


Think about a recipe, for preparing something to eat.

A recipe has a clear, defined end. It addresses a specific question. It shows someone - who can be assumed to have some basic knowledge already - how to achieve something.

Someone who has never cooked before can't be expected to follow a recipe with success, so a recipe is not a substitute for a cooking lesson. At the same time, someone who reads a recipe would be irritated to find that it tries to teach basics that they know already,
or contains irrelevant discussion of the ingredients.

=================

How to write good how-to guides
-------------------------------

..  sidebar:: How-to characteristics

    * focused on tasks or problems
    * assume the user knows what they want to achieve
    * action and only action
    * no digression, explanation, teaching

Provide a series of steps
~~~~~~~~~~~~~~~~~~~~~~~~~

**How-to guides must contain a list of steps, that need to be followed in order** (just like tutorials do). You don’t have to start at the very beginning, just at a reasonable starting point. How-to guides should be reliable, but they don’t need to have the cast-iron repeatability of a tutorial.


Focus on results
~~~~~~~~~~~~~~~~~~~~

**How-to guides must focus on achieving a practical goal.** Anything else is a distraction. As in tutorials, detailed explanations are out of place here.


Solve a particular problem
~~~~~~~~~~~~~~~~~~~~~~~~~~

**A how-to guide must address a specific question or problem**: *How do I …?*

This is one way in which how-to guides are distinct from tutorials: when it comes to a how-to guide, the reader can be assumed to know *what* they should achieve, but don’t yet know *how* - whereas in the tutorial, *you* are responsible for deciding what things the reader needs to know about.


Don't explain concepts
~~~~~~~~~~~~~~~~~~~~~~~

**A how-to guide should not explain things.** It’s not the place for discussions of that kind; they will simply get in the way of the action. If explanations are important, link to them.


Allow for some flexibility
~~~~~~~~~~~~~~~~~~~~~~~~~~

**A how-to guide should allow for slightly different ways of doing the same thing.** It needs just enough flexibility in it that the user can see how it will apply to slightly different examples from the one you describe, or understand how to adapt it to a slightly different system or configuration from the one you’re assuming. Don’t be so specific that the guide is useless for anything except the exact purpose you have in mind.


Leave things out
~~~~~~~~~~~~~~~~

**Practical usability is more valuable than completeness.** Tutorials need to be complete, end-to-end guides; how-to guides do not. They can start and end where it seems appropriate to you. They don’t need to mention everything that there is to mention either, just because it is related to the topic. A bloated how-to guide doesn’t help the user get speedily to their solution.


Name guides well
~~~~~~~~~~~~~~~~

**The title of a how-to document should tell the user exactly what it does.** *How to create a class-based view* is a good title. *Creating a class-based view* or worse, *Class-based views*, are not.

==============

The language of how-to guides
-----------------------------

*This guide shows you how to...*
    Describe clearly the problem or task that the guide shows the user how to solve.
*If you want x, do y. To achieve w, do z.*
    Use conditional imperatives.
*Refer to the x reference guide for a full list of options.*
    Don't pollute your practical how-to guide with every possible thing the user might do related to x.

================

Example from Divio's documentation
----------------------------------

Have a look at `our how-to guides <https://docs.divio.com/en/latest/how-to>`_.

.. image:: /images/django-how-to-example.png
   :alt: 'Django how-to example'
   :align: right
   :width: 379

Each one of these is an answer to a question, or problem: *how do I...?* Each title can clearly be preceded by the
words “How to”. Each one is a recipe, that takes you through the steps required to complete a specific task.

Although both the tutorials and the how-to guides serve the needs of the user, the tutorials are led by the author who
knows what the user needs to know, while the how-to guides are led by the user who asks the questions.
