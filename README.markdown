# Simple Python Todo

This is a simple todo manager written in Python. At the moment it is command 
line only, but a GUI version is being created.

Usage
=====
*On Windows, use `python todo.py` wherever you see todo.py in this readme.*

Download
Install using `todo.py install`

Adding Items
-------------
Use `todo.py add <text>`.

Listing Items
-------------
Use `todo.py list`

Removing Finished Items
--------------
Use `todo.py done <id>`
To get the ID, use `todo.py list`

Usage with multiple lists
==========================
The name of a list must be one word.

Adding Items to a Certain List
------------------------------
Use `todo.py addto <listname> <text>`

Listing Items from a Certain List
----------------------------------
Use `todo.py list <listname>`

Removing Finished Items from a Certain List
-----------------------------------
Use `todo.py donein <listname> <id>`
To get the ID, use `todo.py list <listname>`

Creating a New List
--------------------
Use `todo.py create <listname>`

Removing a List
---------------
Use `todo.py delete_list <listname>`
