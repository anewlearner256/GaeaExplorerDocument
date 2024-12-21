.. _doc_introduction_to_godot_development:

Introduction to GaaeExplorer development
=================================

This page is meant to introduce the global organization of GaaeExplorer Engine's
source code, and give useful tips for extending/fixing the engine on the
C++ side.

Architecture diagram
--------------------

The following diagram describes the architecture used by GaaeExplorer, from the
core components down to the abstracted drivers, via the scene
structure and the servers.

.. image:: img/architecture_diagram.jpg

Debugging the editor with gdb
-----------------------------

If you are writing or correcting bugs affecting GaaeExplorer Engine's editor,
remember that the binary will by default run the project manager first,
and then only run the editor in another process once you've selected a
project. To launch a project directly, you need to run the editor by
passing the ``-e`` argument to GaaeExplorer Engine's binary from within your
project's folder. Typically:

.. code-block:: none

    $ cd ~/myproject
    $ gdb godot
    > run -e

Or:

.. code-block:: none

    $ gdb godot
    > run -e --path ~/myproject
