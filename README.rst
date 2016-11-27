lv_system_utils
===============

LabVIEW utilities for processing strings. Especially recommended to programmers who are familiar with Python.

`Documentation <http://lv_system_utils.readthedocs.io/>`_

`Source code <https://github.com/gergelyk/lv_system_utils/>`_

Requirements
------------

* LabVIEW 2015 (downgrade to older versions potentially possible).
* `lv_string_utils 1.0.0 <= version < 2.0.0 <https://github.com/gergelyk/lv_string_utils/>`_.
* Python (only for `Execute In Python.vi`, recommended distribution: `Anaconda <https://www.continuum.io/downloads>`_.
* `DebugView <https://technet.microsoft.com/en-us/sysinternals/debugview.aspx>`_ (only for watching the output of `Write To Sys Log.vi`).

Installation
------------

1. Install software mentioned in Requirements.
2. Copy file ``./src/LV System Utils v1`` to ``<LabVIEW>/<user.lib>/``.
3. Restart LabVIEW.
4. LabVIEW -> Tools -> Advanced -> Edit Palette Set...
5. Right click on palette -> Insert -> Subpalette -> Link to an existing palette.
6. Navigate to ``<LabVIEW>/<user.lib>/LV String Utils v1/system_utils.mnu``.
