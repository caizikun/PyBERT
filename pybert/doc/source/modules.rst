Modules in *pybert* package
---------------------------

pybert - Main *PyBERT* class definition, as well as some helper classes.
************************************************************************

.. automodule:: pybert.pybert

.. autoclass:: pybert.pybert.PyBERT
   :members:

.. autoclass:: pybert.pybert.TxOptThread
   
.. autoclass:: pybert.pybert.RxOptThread
   
.. autoclass:: pybert.pybert.CoOptThread
   
.. autoclass:: pybert.pybert.TxTapTuner
   
pybert_cntrl - Model control logic.
***********************************

.. automodule:: pybert.pybert_cntrl
   :members: my_run_sweeps, my_run_simulation, update_results, update_eyes

pybert_view - Main GUI window layout definition.
************************************************

.. automodule:: pybert.pybert_view
   :members: MyHandler, RunSimThread

pybert_util - Various utilities used by other modules.
******************************************************

.. automodule:: pybert.pybert_util
   :members: moving_average, find_crossing_times, find_crossings, calc_jitter, make_uniform, calc_gamma, calc_G, calc_eye, make_ctle, trim_impulse, import_qucs_csv

pybert_plot - Plot definitions for the *PyBERT* GUI.
****************************************************

.. automodule:: pybert.pybert_plot

pybert_help - Contents of the *Help* tab of the *PyBERT* GUI.
*************************************************************

.. automodule:: pybert.pybert_help

dfe - DFE behavioral model.
***************************

.. automodule:: pybert.dfe
   :members: LfilterSS, DFE

cdr - CDR behavioral model.
***************************

.. automodule:: pybert.cdr
   :members: CDR

