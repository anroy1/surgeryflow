# surgeryflow
<img src="logo_surgeryflow.png" alt="Alt Text" width="25%">

SURGERYFLOW IS STILL A WORK IN PROGRESS - DO NOT USE

The SurgeryFlow pipeline aims to become  a fully automated and reproducible dMRI processing pipeline designed for optimal performance in a neurosurgical context. It is based on \
the TractoFlow and the RecoBundleX pipelines wrapped in a nextflow. Its objectives are:
- Including data management functions to receive its inputs in the DICOM format and to generate outputs already compatible for clinical tools (PACS console, surgical \
  navigation, ...)
- Improve its processing time significantly (GPU processing, wrapping of Tractoflow and RBxFlow, Freesurfer Synth integration)
- Democratize its access to non computer scientists users by simplifying its command.
- Possibly devellop a fMRI profile for functionnal map based bundle segmentation.

The TractoFlow pipeline is a fully automated and reproducible dMRI processing pipeline. \
TractoFlow takes raw DWI, b-values, b-vectors, T1 weighted image (and a reversed phase encoded b=0 if available) to process DTI, \
fODF metrics and a whole brain tractogram.

TractoFlow documentation is available here:

[https://tractoflow-documentation.readthedocs.io](https://tractoflow-documentation.readthedocs.io)

