These files are from my OS Final Project where we implemented a shell.
========
The provided makefile can be used to build your project,
 
.. code-block:: console

   $ make          # Equivalent to `make all`
   $ make all      # Equivalent to `make release debug` (default target)
   $ make release  # Release build in release/ -- no debugging messages
   $ make debug    # Debug build in debug/ -- includes assertions and debugging messages
   $ make clean    # Removes build files (release/ and debug/ directories)

A reference implementation is provided in ``reference/bigshell``.
