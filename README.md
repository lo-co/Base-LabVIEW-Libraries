# Base LabVIEW Libraries: A Collection

This repository is intended to contain a collection of code created in LabVIEW for wider distribution.  Code that is included here is:

* in a functional and mostly static state.  This means that the API has not been changed in sometime and is not intended to be changed in the future.  This code can be used as is.  It does not mean that the code will not be changed or cleaned up.
* compiled and packaged into vipm modules.  All code that is in this repository has been tested against the built library and is considered safe for redistribution.  Package specs and built packages can be found in the ``vipm`` folder.

In addition to fully custom code, the ESF library provided by NI has been repackaged and placed in the ``Reusable/Session APIs/`` folder.  The reason for this is to imporve portability.  In the currently available vipm module, this package is deployed to ``user.lib``.  Unfortunately, this is not a default folder for searching at startup in LabVIEW.  The new deployment location is in ``vi.lib``.
