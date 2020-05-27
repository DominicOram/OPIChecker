# OPIChecker
The checker from https://github.com/ISISComputingGroup/ibex_gui/tree/master/base/uk.ac.stfc.isis.ibex.opis but with all the IBEX GUI stuff removed

To run:
* `python -m venv my_venv`
* `my_venv/Scripts/activate`
* `pip install -r requirements.txt`
* `python check_opi_format.py -file test_checks.opi`, this should run tests and print a number of problems with the OPIChecker

`check_OPI_format_logs` should then contain logs that you can hook into you CI system