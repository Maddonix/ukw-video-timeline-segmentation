========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |codecov|
        | |scrutinizer| |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/ukw-video-timeline-segmentation/badge/?style=flat
    :target: https://ukw-video-timeline-segmentation.readthedocs.io/
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.com/Madonix/ukw-video-timeline-segmentation.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.com/github/Madonix/ukw-video-timeline-segmentation

.. |requires| image:: https://requires.io/github/Madonix/ukw-video-timeline-segmentation/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/Madonix/ukw-video-timeline-segmentation/requirements/?branch=master

.. |codecov| image:: https://codecov.io/gh/Madonix/ukw-video-timeline-segmentation/branch/master/graphs/badge.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/Madonix/ukw-video-timeline-segmentation

.. |codacy| image:: https://img.shields.io/codacy/grade/f09520f074854941bce9e6964753af4a.svg
    :target: https://www.codacy.com/app/Madonix/ukw-video-timeline-segmentation
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/Madonix/ukw-video-timeline-segmentation/badges/gpa.svg
   :target: https://codeclimate.com/github/Madonix/ukw-video-timeline-segmentation
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/ukw-video-timeline-segmentation.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/ukw-video-timeline-segmentation

.. |wheel| image:: https://img.shields.io/pypi/wheel/ukw-video-timeline-segmentation.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/ukw-video-timeline-segmentation

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/ukw-video-timeline-segmentation.svg
    :alt: Supported versions
    :target: https://pypi.org/project/ukw-video-timeline-segmentation

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/ukw-video-timeline-segmentation.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/ukw-video-timeline-segmentation

.. |commits-since| image:: https://img.shields.io/github/commits-since/Madonix/ukw-video-timeline-segmentation/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/Madonix/ukw-video-timeline-segmentation/compare/v0.0.0...master


.. |scrutinizer| image:: https://img.shields.io/scrutinizer/quality/g/Madonix/ukw-video-timeline-segmentation/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/Madonix/ukw-video-timeline-segmentation/


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: MIT license

Installation
============

::

    pip install ukw-video-timeline-segmentation

You can also install the in-development version with::

    pip install https://github.com/Madonix/ukw-video-timeline-segmentation/archive/master.zip


Documentation
=============


https://ukw-video-timeline-segmentation.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
