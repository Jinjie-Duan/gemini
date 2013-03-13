##############################
The Gemini browser interface
##############################

Currently, the majority of gemini's functionality is available via a command-line
interface.  However, we are developing a browser-based interface for easier exploration
of gemini databases created with the ``gemini load`` command.

Ironically, as of now, one must launch said browser from the command line as
follows (where ``my.db`` should be replaced with the name of the gemini database
you would like to explore).

.. code-block:: bash

    $ gemini browser my.db

At this point, the gemini browser is running on port 8088 on your local machine.
Open a web browser to http://localhost:8088/query  You should see something like:

.. image:: ../images/browser-query.png
    :width: 600pt 