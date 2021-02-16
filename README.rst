Galaxy tool wrappers for DIMSpy
===============================
|Build Status (last commit)| |Build Status (weekly global test)| |galaxy-eu| |Git| |Bioconda| |License|

Galaxy tool wrappers for Python package DIMSpy: data processing of direct-infusion mass spectrometry (DIMS)-based metabolomics and lipidomics data

Source code: https://github.com/computational-metabolomics/dimspy

PyPI (The Python Package Index): https://pypi.org/project/dimspy


Version
--------
v2.0.0+Galaxy0 (`DIMSpy v2.0.0 <https://pypi.org/project/dimspy/2.0.0/>`_)


Galaxy
-------
`Galaxy <https://galaxyproject.org>`_ is an open, web-based platform for data intensive biomedical research. Whether on the free public server or your own instance, you can perform, reproduce, and share complete analyses. 


Credits
-------

**Authors and contributors**
 - Ralf J. M. Weber (r.j.weber@bham.ac.uk) - `University of Birmingham (UK) <https://www.birmingham.ac.uk/staff/profiles/biosciences/weber-ralf.aspx>`__
 - Thomas N. Lawson (t.n.lawson@bham.ac.uk) - `University of Birmingham (UK) <http://www.birmingham.ac.uk/index.aspx>`__
 - Martin R. Jones (martin.jones@eawag.ch) - `Eawag  (Switzerland) <https://www.eawag.ch/en/aboutus/portrait/organisation/staff/profile/martin-jones/show/>`_


**DIMSpy acknowledges support from the following funders:**
 - BBSRC, grant number BB/M019985/1
 - European Commission's H2020 programme, grant agreement number 654241
 - Wellcome Trust, grant number 202952/Z/16/Z


Bugs
----
Please report any bugs that you find `here <https://github.com/computational-metabolomics/dimspy-galaxy/issues>`_.
Or fork the repository on `GitHub <https://github.com/computational-metabolomics/dimspy-galaxy/>`_
and create a pull request (PR). We welcome all contributions, and we
will help you to make the PR if you are new to `git`.


Changes
-------
v2.0.0+galaxy0
  - First release (Python 3-based version `DIMSpy <https://pypi.org/project/dimspy/2.0.0/>`_)

v1.4.0+galaxy0
  - Final release (Python 2-based version `DIMSpy <https://pypi.org/project/dimspy/1.4.0/>`_)


Licenses
-------
DIMSpy and Galaxy tools are released under the GNU General Public License v3.0 (see `LICENSE file <https://github.com/computational-metabolomics/dimspy-galaxy/blob/master/LICENSE>`_)

**Third-party licenses and copyright**

RawFileReader reading tool. Copyright © 2016 by Thermo Fisher Scientific, Inc. All rights reserved. See `RawFileReaderLicense <https://github.com/computational-metabolomics/dimspy/blob/master/RawFileReaderLicense.rst>`_ for licensing information.
Using DIMSpy software for processing Thermo Fisher Scientific *.raw files implies the acceptance of the RawFileReader license terms.
Anyone receiving RawFileReader as part of a larger software distribution (in the current context, as part of DIMSpy) is considered an "end user" under
section 3.3 of the RawFileReader License, and is not granted rights to redistribute RawFileReader.


.. |Build Status (last commit)| image:: https://github.com/computational-metabolomics/dimspy-galaxy/workflows/Galaxy%20Tool%20Linting%20and%20Tests%20for%20push%20and%20PR/badge.svg
   :target: https://github.com/computational-metabolomics/dimspy-galaxy/actions?query=workflow%3A%22Galaxy+Tool+Linting+and+Tests+for+push+and+PR%22

.. |Build Status (weekly global test)| image:: https://github.com/computational-metabolomics/dimspy-galaxy/workflows/Weekly%20global%20Tool%20Linting%20and%20Tests/badge.svg
   :target: https://github.com/computational-metabolomics/dimspy-galaxy/actions?query=workflow%3A%22Weekly+global+Tool+Linting+and+Tests%22

.. |Git| image:: https://img.shields.io/badge/repository-GitHub-blue.svg?style=flat&maxAge=3600
   :target: https://github.com/computational-metabolomics/dimspy

.. |galaxy-eu| image:: https://img.shields.io/badge/usegalaxy-.eu-brightgreen?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAASCAYAAABB7B6eAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAACXBIWXMAAAsTAAALEwEAmpwYAAACC2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iWE1QIENvcmUgNS40LjAiPgogICA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPgogICAgICA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIgogICAgICAgICAgICB4bWxuczp0aWZmPSJodHRwOi8vbnMuYWRvYmUuY29tL3RpZmYvMS4wLyI+CiAgICAgICAgIDx0aWZmOlJlc29sdXRpb25Vbml0PjI8L3RpZmY6UmVzb2x1dGlvblVuaXQ+CiAgICAgICAgIDx0aWZmOkNvbXByZXNzaW9uPjE8L3RpZmY6Q29tcHJlc3Npb24+CiAgICAgICAgIDx0aWZmOk9yaWVudGF0aW9uPjE8L3RpZmY6T3JpZW50YXRpb24+CiAgICAgICAgIDx0aWZmOlBob3RvbWV0cmljSW50ZXJwcmV0YXRpb24+MjwvdGlmZjpQaG90b21ldHJpY0ludGVycHJldGF0aW9uPgogICAgICA8L3JkZjpEZXNjcmlwdGlvbj4KICAgPC9yZGY6UkRGPgo8L3g6eG1wbWV0YT4KD0UqkwAAAn9JREFUOBGlVEuLE0EQruqZiftwDz4QYT1IYM8eFkHFw/4HYX+GB3/B4l/YP+CP8OBNTwpCwFMQXAQPKtnsg5nJZpKdni6/6kzHvAYDFtRUT71f3UwAEbkLch9ogQxcBwRKMfAnM1/CBwgrbxkgPAYqlBOy1jfovlaPsEiWPROZmqmZKKzOYCJb/AbdYLso9/9B6GppBRqCrjSYYaquZq20EUKAzVpjo1FzWRDVrNay6C/HDxT92wXrAVCH3ASqq5VqEtv1WZ13Mdwf8LFyyKECNbgHHAObWhScf4Wnj9CbQpPzWYU3UFoX3qkhlG8AY2BTQt5/EA7qaEPQsgGLWied0A8VKrHAsCC1eJ6EFoUd1v6GoPOaRAtDPViUr/wPzkIFV9AaAZGtYB568VyJfijV+ZBzlVZJ3W7XHB2RESGe4opXIGzRTdjcAupOK09RA6kzr1NTrTj7V1ugM4VgPGWEw+e39CxO6JUw5XhhKihmaDacU2GiR0Ohcc4cZ+Kq3AjlEnEeRSazLs6/9b/kh4eTC+hngE3QQD7Yyclxsrf3cpxsPXn+cFdenF9aqlBXMXaDiEyfyfawBz2RqC/O9WF1ysacOpytlUSoqNrtfbS642+4D4CS9V3xb4u8P/ACI4O810efRu6KsC0QnjHJGaq4IOGUjWTo/YDZDB3xSIxcGyNlWcTucb4T3in/3IaueNrZyX0lGOrWndstOr+w21UlVFokILjJLFhPukbVY8OmwNQ3nZgNJNmKDccusSb4UIe+gtkI+9/bSLJDjqn763f5CQ5TLApmICkqwR0QnUPKZFIUnoozWcQuRbC0Km02knj0tPYx63furGs3x/iPnz83zJDVNtdP3QAAAABJRU5ErkJggg==
   :target: http://usegalaxy.eu

.. |Bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat&maxAge=3600
   :target: http://bioconda.github.io/recipes/dimspy/README.html

.. |License| image:: https://img.shields.io/badge/License-GPL%20v3-blue.svg
   :target: https://www.gnu.org/licenses/gpl-3.0.html
