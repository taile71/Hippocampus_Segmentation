# Hippocampus_Segmentation

Build an end-to-end AI system which features a machine learning algorithm that integrates into a clinical-grade viewer and automatically measures hippocampal volumes of new patients, as their studies are committed to the clinical imaging archive.

Local Environment:
- PyTorch (preferably with CUDA)
- nibabel
- matplotlib
- numpy
- pydicom
- Pillow (should be installed with pytorch)
- tensorboard

Software products for emulating the clinical network. Install and configure:
- Orthanc server for PACS emulation
- OHIF zero-footprint web viewer 
- DCMTK tools for testing and emulating a modality. Note that if you are running a Linux distribution
