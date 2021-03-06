.. Osmium documentation master file, created by
   sphinx-quickstart on Wed Sep  7 23:11:24 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. _osmium_index:

========================================
Osmium - Identify, collaborate, discover
========================================

.. image:: /_static/pmr.png
   :width: 15em
   :align: right
   :target: https://models.physiomeproject.org
   :alt: Examples from the Physiome Model Repository.
   
Osmium is the software framework being developed to power the next generation `Physiome Model Repository <https://models.physiomeproject.org>`_ (PMR) and the VPH/Physiome Portal (PHYSIOME). Deployed instances of the Osmium framework provide collaborative repositories for archiving, sharing, discovering, reusing, and identifying computational models and associated data. Models and associated data encoded in standard formats can be discovered when placed in freely accessible repositories. Including comprehensive descriptions enables other scientists to reuse your work.

Osmium began as a refactoring of `the software stack <http://dx.doi.org/10.1093/bioinformatics/btq723>`_ behind the second generation of PMR (the `CellML model repository <http://dx.doi.org/10.1093/bioinformatics/btn390>`_ being the first generation), and the additional new features to meet the growing demands for collaborative, reproducible, and reusable modelling in the Physiome/VPH communities. Supporting PHYSIOME `curation and publication workflows <https://dx.doi.org/10.6084/m9.figshare.3811065>`_ will, furthermore, require new features be implemented in Osmium beyond the current capabilities of PMR. Enabling the integration of models published in PHYSIOME, and other collaborating community portals, will similarly require extensions to existing features in PMR and the addition of new features.

In the following, we briefly introduce the various constituents of the Osmium framework and describe their role in the project.

.. _osmium_pmr:

Physiome Model Repository
=========================

The `Physiome Model Repository <https://models.physiomeproject.org>`_ (PMR) is an extensive repository of computational models, predominantly of physiological systems but also containing a range of mathematical models (including some classical physics examples). As various components of the Osmium framework are developed they will be incorporated into the PMR instance. As such, the :ref:`PMR documentation <abi-pmr2-index>` included here will be updated to reflect the modifications, additions, and capabilities.

PMR is the exemplar repository that provides the primary public view of Osmium.

.. toctree::
   :hidden:
   
   pmr/index

.. _osmium_repodono:

RepoDono
========

`RepoDono <https://github.com/repodono>`_ is the core software stack being developed to replace the `current software stack <https://github.com/PMR2>`_. 