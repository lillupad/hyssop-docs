Usage
=====

.. _installation:

Quick start
------------

To use hyssop.js, first install it using npm:

.. code-block:: console

    $ npm install create-hyssop
   

Then use ``create-hyssop`` with either

.. code-block:: console

    $ npm create hyssop -y

or

.. code-block:: console
    
    $ npx create-hyssop -y

.. note::

    both of these commands produce the same output

after that, your current directory should look like this:
:: 
    project-directory
    ├── index.html
    ├── main.html
    ├── hyssop.min.js

finally, start a dev server with

.. code-block:: console

    $ python3 -m http.server

and open the port in your browser.
