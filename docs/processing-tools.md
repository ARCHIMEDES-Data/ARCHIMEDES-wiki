# Tool Catalogue

ARCHIMEDES provides access to a wide range of analysis tools through the CBRAIN platform. While CBRAIN offers over 100 analysis tools, this catalogue highlights a selection of the most commonly used tools to help you get started. If you are interested in using a tool that is not listed, please don't hesitate to contact the ARCHIMEDES team.

**ℹ️Note**: The ARCHIMEDES Tool Catalogue is continuously expanding. Additional tools, including cardiac imaging analysis tools, will be added as they become available. If you are interested in a specific analysis tool, please contact us at [ARCHIMEDES@ottawaheart.ca](...).

## File Format Conversion

Tools for converting research data between commonly used medical imaging and neuroimaging file formats.

| Tool | Description |
|------|-------------|
| Dcm2mnc | Converts DICOM images to the MINC file format. |
| Dcm2nii | Converts DICOM images to the NIfTI file format. |
| Dicom2hrrt | Converts DICOM PET images to the HRRT file format. |
| Minc2analyze | Converts MINC images to the Analyze file format. |
| Minc2jiv | Converts MINC images for visualization in the JIV viewer. |
| MincConvert | Converts MINC images between supported MINC formats. |
| Mnc2nii | Converts MINC images to the NIfTI file format. |
| Nii2mnc | Converts NIfTI images to the MINC file format. |

## File Operations

Tools for extracting files from existing datasets.

| Tool | Description |
|------|-------------|
| **SimpleFileExtractor** | Extracts files from existing datasets by matching specified filename patterns. |

## Structural MRI

Tools for processing and and analyzing brain anatomy and structural images.This includes cortical surfaces, tissue segmentation, and quality control.

| Tool | Description |
|------|-------------|
| BigBrainWarp | Maps neuroimaging data to the BigBrain anatomical atlas for advanced brain mapping and analysis. |
| CIVET | Processes structural MRI data to generate cortical surface models and measure cortical thickness. |
| CIVET QC Tool | Performs quality control on CIVET processing outputs to help assess data quality. |
| CivetCombiNer | Combines outputs from multiple CIVET processing steps into a unified dataset. |
| Civetmacaque | Processes structural MRI data from macaque brains using the CIVET pipeline. |
| csv_Neocivet | Processes neonatal structural MRI data using the NeoCIVET pipeline. |
| FreeSurferRecoNAll | Performs automated cortical surface reconstruction and anatomical segmentation using FreeSurfer. |
| Fsl_aNat | Performs automated preprocessing of structural MRI data using FSL. |
| FslFast | Segments brain tissue into gray matter, white matter, and cerebrospinal fluid. |
| FSLFirst | Segments subcortical brain structures from structural MRI images. |
| hippunfold | Segments and analyzes the hippocampus using structural MRI data. |
| NuCorrect | Corrects intensity non-uniformity (bias field) in MRI images. |
| ReconAll | Runs the standard FreeSurfer pipeline for structural MRI analysis. |
| ReconAllLongi | Performs longitudinal structural MRI analysis across multiple time points using FreeSurfer. |

## Functional MRI (fMRI) Analysis & Preprocessing

Tools for preprocessing (preparing and cleaning), analyzing, and visualizing functional MRI (fMRI) data to study brain activity and functional connectivity.

| Tool | Description |
|------|-------------|
| FMRIprepBidsSubject | Preprocesses BIDS-formatted functional MRI datasets using the fMRIPrep workflow. |
| FslFeat | Performs statistical analysis of functional MRI data using the FSL FEAT pipeline. |
| FslFlirt | Registers and aligns functional and structural MRI images. |
| FslMelodic | Performs independent component analysis (ICA) to identify functional brain networks. |
| ICA_AROMA | Identifies and removes motion-related artifacts from functional MRI data. |
| McFlirt | Corrects head motion in functional MRI time series. |
| MICAPE | Processes multimodal MRI data using the MICAPE workflow. |
| TAPAS PhysIO | Models and corrects physiological noise in functional MRI data. |
| melodic | Performs independent component analysis (ICA) to identify functional brain networks. |

## Tractography (Diffusion MRI)

Tools for processing and analyzing diffusion MRI data to map white matter pathways and assess brain connectivity.

| Tool | Description |
|------|-------------|
| FslBedpostx | Estimates diffusion parameters and fiber orientations for diffusion MRI analysis. |
| ndmg | Processes diffusion MRI data to generate structural brain connectivity networks. |

## Arterial Spin Labeling (ASL)

Tools for processing and analyzing Arterial Spin Labeling (ASL) MRI data to measure tissue perfusion and cerebral blood flow

| Tool | Description |
|------|-------------|
| ASLPrep | Preprocesses ASL MRI data using a standardized workflow for perfusion imaging analysis. |
| oxford_asl | Quantifies cerebral blood flow and other perfusion measures from ASL MRI data. |

## PET 

Tools for processing and analyzing Positron Emission Tomography (PET) data.

| Tool | Description |
|------|-------------|
| APPIANPET | Processes and analyzes PET imaging data using the APPIAN PET analysis pipeline. |

## EEG / MEG

Tools for processing and analyzing electroencephalography (EEG) data to support the study of brain electrical activity.

| Tool | Description |
|------|-------------|
| Brainstorm | Processes, analyzes, and visualizes EEG and MEG data. |
| HarMNqEEG | Harmonizes and analyzes quantitative EEG (qEEG) data across studies. |
| qEEG | Analyzes quantitative EEG data to assess brain activity and function. |

## Brain Lesion Segmentation

Tools for identifying, segmenting, and analyzing brain lesions from medical imaging data.

| Tool | Description |
|------|-------------|
| BraTSPipeline | Segments and analyzes brain tumors and lesions from MRI data using the BraTS workflow. |
| lesionBrain | Automatically identifies and segments brain lesions from MRI images. |


## Neuroimaging Processing Tools

Tools for processing and analyzing neuroimaging data.

| Tool | Description |
|------|-------------|
| FslBet | Removes non-brain tissue from MRI images using FSL's Brain Extraction Tool (BET). |
| Mincmath | Performs mathematical operations on MINC image files. |
| Mincresample | Resamples MINC images to modify their resolution, orientation, or spatial dimensions. |

## Statistical Analysis

Tools for performing statistical analysis of research data.

| Tool | Description |
|------|-------------|
| FslRandomise | Performs non-parametric statistical analysis of neuroimaging data using permutation testing. |
| Fslstats | Calculates statistical measures from neuroimaging data. |
| Mincaverage | Computes the average of multiple MINC image files. |
| Mincpik | Generates image previews from MINC files for visualization and quality assessment. |

## Genetics

Tools for processing and analyzing genetic data.

| Tool | Description |
|------|-------------|
| Biomarkers | Identifies and analyzes genetic biomarkers associated with biological processes and disease. |
| cellranger-count | Processes single-cell sequencing data by aligning reads, counting gene expression, and generating feature-barcode matrices. |

## Genomics

Tools for processing and analyzing genomic data.

| Tool | Description |
|------|-------------|
| ePRS_5HTT | Calculates expression-based polygenic risk scores (ePRS) related to the serotonin transporter (5-HTT) pathway. |
| imputePrepSanger | Prepares genotype data for imputation using the Sanger Imputation Service. |
| MethylationPipeliNe | Processes and analyzes DNA methylation data. |
| mfannot | Annotates mitochondrial genome sequences and identifies genomic features. |

## Pipeline Development

Tools for developing, packaging, and managing analysis pipelines.

| Tool | Description |
|------|-------------|
| BoutiquesDescriptorMaker | Creates Boutiques descriptors for packaging and describing analysis tools to support reproducible execution across computing platforms. |


