Project work
============

Choose a project work. There are three projects to choose from:

1. biological sequence analysis (part07)
2. regression analysis on medical data (part08)
3. fossil data analysis 

The fossil data analysis project is currently not integrated to the TMC system, so for that, see the instructions from the `course page <https://studies.helsinki.fi/courses/cur/hy-CUR-139313455/Open_uni_Data_Analysis_with_Python_Summer_2021>`_.

For the two first projects (part07 and part08), download the exercises
and/or notebooks from the TMC server.
Then try to solve as many exercises as you can.
Then submit your solutions to the TMC server.
Note that the TMC server is only used here for helping you
to proceed with the project work. Your final project work
returned to Moodle can include partial solutions.

.. note:: If you are using VS Code you can run tests for the jupyter notebook by right clicking the file in the ``src/`` folder.

The projects differ a lot in their workflow. See the below sections
on individual projects to see in detail how solving, testing and reporting
of exercises are done in each project.

Save the report as a Jupyter notebook file (with ``ipynb`` extension)
and submit this file to Moodle. After this you will need to give feedback for your own
report and two other reports. See the `course page <https://studies.helsinki.fi/courses/cur/hy-CUR-139313455/Open_uni_Data_Analysis_with_Python_Summer_2021>`_ for instructions on this peer-review process.  

Sequence analysis
-----------------

Download part 7 from tmc after you have completed the required number of part 6
as usual. The ``src``-folder contain a jupyter notebook
``project_notebook_sequence_analysis.ipynb``. Run the notebook and fill in the
cells as instructed. You may run tmc test to see if the functions seem work as required. 
The tests are not comprehensive, os a passing test may not imply a perfect solution, nor 
does a failing test necessarily mean the there are critical errors. 
Submitting may not work especially if you download content from the internet as
part of your code.

Next to each exercise in the report there are also two text boxes for you
to fill. In the first box, in your own words, describe the idea of the
solution to the exercise. In the second box analyse the results, including how
the program worked with the given example input or your own examples. Make sure
the notebook includes your solutions and looks readable, and then submit the
resulting notebook to Moodle.

NOTE. Exercises in section "Stationary and equilibrium distributions (extra)"
(exercises 20, 21, and 22) are not obligatory. Thus, you only need to do
19 exercises, if you are aiming to get full points.

Regression analysis
-------------------

Read the introduction ``introduction-to-regression-analysis.pdf`` from the `course webpage <https://studies.helsinki.fi/courses/cur/hy-CUR-139313455/Open_uni_Data_Analysis_with_Python_Summer_2021>`_.

Write solutions to exercises directly into the cells of the given Jupyter notebook.
Do not modify lines that say ``# exercise x``; without those the tests won't work.
Don't use additional cells, and do in each cell exactly as the instructions say.
Save the file and run test normally. The tests read and execute directly the cells
of the notebook.
Make sure the notebook includes you solutions and looks readable,
and then submit the resulting notebook to Moodle.

Running tests when peer-reviewing students notebooks
====================================================

If you want, you can run tests on the work you are reviewing, to help
assess the correctness of the solutions. Note that there can be bugs in
the tests too.

.. warning:: Back up your own solutions to make sure you don't accidentally delete them when testing other student's work.

* Replace your ``.ipynb`` solutions with one downloaded from the peer review. 

* Make sure that the name is correct (``project_notebook_regression_analysis.ipynb`` or ``project_notebook_sequence_analysis.ipynb``).

* Run tests normally.

