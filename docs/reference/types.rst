.. meta::
  :description: rocSOLVER documentation and API reference library
  :keywords: rocSOLVER, ROCm, API, documentation

.. _rocsolver-types:

********************************************************************
rocSOLVER Types
********************************************************************

rocSOLVER uses most types and enumerations defined in rocBLAS for the general operation and
dense matrix computations, and some defined in rocSPARSE for sparse matrix computations (direct solvers).
For more information, see the :doc:`rocBLAS types <rocblas:reference/datatypes>` and
:doc:`rocSPARSE types <rocsparse:reference/types>` documentation.
Next we present additional types, only used in rocSOLVER, that extend the rocBLAS and rocSPARSE APIs.


Additional types
================

.. contents:: List of additional types
   :local:
   :backlinks: top

rocblas_direct
---------------
.. doxygenenum:: rocblas_direct

rocblas_storev
---------------
.. doxygenenum:: rocblas_storev

rocblas_svect
---------------
.. doxygenenum:: rocblas_svect

rocblas_srange
---------------
.. doxygenenum:: rocblas_srange

rocblas_evect
---------------
.. doxygenenum:: rocblas_evect

rocblas_workmode
------------------
.. doxygenenum:: rocblas_workmode

rocblas_eform
---------------
.. doxygenenum:: rocblas_eform

rocblas_erange
---------------
.. doxygenenum:: rocblas_erange

rocblas_eorder
---------------
.. doxygenenum:: rocblas_eorder

rocblas_esort
---------------
.. doxygenenum:: rocblas_esort

rocblas_layer_mode_flags
------------------------
.. doxygentypedef:: rocblas_layer_mode_flags

rocsolver_rfinfo
------------------------
.. doxygentypedef:: rocsolver_rfinfo

rocsolver_rfinfo_mode
------------------------
.. doxygenenum:: rocsolver_rfinfo_mode
