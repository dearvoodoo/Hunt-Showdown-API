.. _general:

=======
General
=======

This is the module guide for the general module. You will
find detailed docs about usage and commands.

``[p]`` is considered as your prefix. (Default: ``!`` or ``/``)

.. _general-usage:

-----
Usage
-----

This module includes a miscellaneous group of games, useful
tools, and informative commands such as ``serverinfo``.

.. _general-commands:

--------
Commands
--------

Here's a list of all commands available for this module.

.. _general-command-8:

^^^^^^^^^
8 (8ball)
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]8 <question>

**Description**

Ask 8 ball a question. 

.. note:: Your question must end with a question mark.

**Arguments**

* ``<question>``: The question you would like to ask 8 ball.

.. _general-command-choose:

^^^^^^
choose
^^^^^^

**Syntax**

.. code-block:: none

    [p]choose <first> <second> [others...]

**Description**

Choose between multiple options.
Options are separated by spaces.

.. note::  There must be at least 2 options to pick from.
.. note::  To denote options which include whitespace, you should enclose the option in double quotes.

**Arguments**

* ``<first>``: The first mandatory option.
* ``<second>``: The second mandatory option.
* ``[others...]``: Any remaining optional options.


.. _general-command-flip:

^^^^
flip
^^^^

**Syntax**

.. code-block:: none

    [p]flip [user]

**Description**

Flip a coin... or a user.

**Arguments**

* ``[user]``: The user to flip. Defaults to flipping a coin if no user is provided.

.. _general-command-lmgtfy:

^^^^^^
lmgtfy
^^^^^^

**Syntax**

.. code-block:: none

    [p]lmgtfy <search_terms>

**Description**

Create a lmgtfy link.

**Arguments**

* ``<search_terms>``: The terms used to generate the lmgtfy link.

.. _general-command-roll:

^^^^
roll
^^^^

**Syntax**

.. code-block:: none

    [p]roll [number=100]

**Description**

Roll a random number. The result will be between 1 and ``<number>``.

**Arguments**

* ``[number]``: The maximum number that can be rolled. Defaults to 100.

.. _general-commands-serverinfo:

^^^^^^^^^^
serverinfo
^^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]serverinfo [details=False]

**Description**

Show server information.

**Arguments**

* ``[details]``: Show extra details about the server when set to True. Defaults to False.

.. _general-commands-stopwatch:

^^^^^^^^^
stopwatch
^^^^^^^^^

**Syntax**

.. code-block:: none

    [p]stopwatch

**Description**

Start or stop the stopwatch.
