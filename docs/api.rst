TorchANI
========

.. autoclass:: torchani.AEVComputer
    :members:
.. autoclass:: torchani.ANIModel
.. autoclass:: torchani.Ensemble
.. autoclass:: torchani.SpeciesConverter
    :members:
.. autoclass:: torchani.EnergyShifter
    :members:
.. autoclass:: torchani.nn.Gaussian


Model Zoo
=========

.. automodule:: torchani.models
.. autoclass:: torchani.models.ANI1x
    :members:
.. autoclass:: torchani.models.ANI1ccx
    :members:


Datasets
========

.. automodule:: torchani.data
.. autofunction:: torchani.data.find_threshold
.. autofunction:: torchani.data.ShuffledDataset
.. autoclass:: torchani.data.CachedDataset
    :members:
.. autofunction:: torchani.data.load_ani_dataset
.. autoclass:: torchani.data.BatchedANIDataset



Utilities
=========

.. automodule:: torchani.utils
.. autofunction:: torchani.utils.pad
.. autofunction:: torchani.utils.pad_atomic_properties
.. autofunction:: torchani.utils.present_species
.. autofunction:: torchani.utils.strip_redundant_padding
.. autofunction:: torchani.utils.map2central
.. autoclass:: torchani.utils.ChemicalSymbolsToInts
    :members:
.. autofunction:: torchani.utils.hessian
.. autofunction:: torchani.utils.vibrational_analysis


NeuroChem
=========

.. automodule:: torchani.neurochem
.. autoclass:: torchani.neurochem.Constants
    :members:
.. autofunction:: torchani.neurochem.load_sae
.. autofunction:: torchani.neurochem.load_atomic_network
.. autofunction:: torchani.neurochem.load_model
.. autofunction:: torchani.neurochem.load_model_ensemble
.. autoclass:: torchani.neurochem.Trainer
    :members:
.. automodule:: torchani.neurochem.trainer


ASE Interface
=============

.. automodule:: torchani.ase
.. autoclass:: torchani.ase.Calculator


TorchANI Optimizater
====================

.. automodule:: torchani.optim
.. autoclass:: torchani.optim.AdamW
