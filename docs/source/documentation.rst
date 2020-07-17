.. _documentation:

Documentation
=============

Usage: myst2canvas [OPTIONS] NOTEBOOK_FILE

* Parse file into quiz and upload to Canvas.

Options:
* -u, --url TEXT    

  * URL of Canvas course.

* -t, --token TEXT    

  * Token string generated by Canvas.

* -f, --token-file TEXT  

  * File containing token string generated by Canvas.

* -c, --course-id TEXT   

  * ID of the course.

* -s, --save-settings    

  * Set flag to save settings for future use.

* -q, --quiz-id TEXT     

  * ID of the quiz, use if updating existing quiz.

* -d, --dump TEXT        

  * File to dump JSON string to.

* -n, --no-upload        

  * Set flag to stop uploading of quiz.

* -h, --hush             

  * Set flag to stop printing other than warnings and errors.

* --help                 

  * Show this message and exit.
  
Example
~~~~~~~

The quiz in the examples folder is fully functional on the latest version of myst2canvas. If your settings are already saved in the config file, this quiz can be uploaded with the following command:

.. code-block:: bash

   myst2canvas .\examples\simpleQuiz.md
  
API
~~~

For using the API, refer to the :ref:`documentation` page.

The following files are documented here:

* :ref:`myst2json.py`

* :ref:`json2canvas.py`

* :ref:`util.py`

.. _myst2json.py:

myst2json.py
""""""""""""

.. automodule:: myst2canvas.myst2json
    :members:

.. _json2canvas.py:

json2canvas.py
""""""""""""""

.. automodule:: myst2canvas.json2canvas
    :members:

.. _util.py:

util.py
"""""""

.. automodule:: myst2canvas.util
    :members:

.. toctree::
   :hidden: