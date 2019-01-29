.. :DataModule:

Data Module
===========

.. currentmodule:: Data

The DataSet object is the interface between the data files and the data treatment and visualziation. It is both responsible for the conversion of raw '.h5'-files into '.nxs'-files as well as plotting these. Extracting values from this object results in a list of values where the first dimension is determined from the number of data files provided.

.. autosummary::
   :nosignatures:

    DataSet.DataSet
    DataSet.DataSet.convertDataFile
    DataSet.DataSet.cut1D
    DataSet.DataSet.plotCut1D
    DataSet.DataSet.cutQE
    DataSet.DataSet.plotCutQE
    DataSet.DataSet.cutPowder
    DataSet.DataSet.plotCutPowder
    DataSet.DataSet.createRLUAxes
    DataSet.DataSet.plotQPlane

    DataSet.DataSet.cutQELine
    DataSet.DataSet.plotCutQELine
    DataSet.binData3D
    DataSet.boundaryQ
    DataSet.calculateGrid3D
    DataSet.createRLUAxes
    DataSet.cut1D
    DataSet.cut1DE
    DataSet.cutPowder
    DataSet.cutQE

    DataSet.plotCutQE

    DataFile.DataFile


.. automodule:: Data
   :members:



DataSet Object and Methods
--------------------------

Object to take care of all data conversion and treatment taking it from raw hdf5 files obtained at the instrument into rebinned data sets converted to S(q,omega). 

.. automodule:: DataSet

.. _DataSet:

.. autoclass:: DataSet
    :members:



Module Functions
----------------

The following is a list of the available functions in the DataSet module. Some of them have wrappers in the DataSet-object methods.

.. automodule:: DataSet
   :members:


DataFile Object and Methods
---------------------------


.. automodule:: DataFile

.. _DataFile:

.. autoclass:: DataFile
    :members:
