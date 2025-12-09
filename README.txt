This dataset includes raw and processed MRI data from a multi-center study of primary glioblastoma, collected across eight collaborating hospitals.
Data were acquired between 2018 and 2025. Participants were adults with histologically confirmed primary glioblastoma who underwent preoperative neuroimaging before surgery.

The dataset contains T1-weighted (pre- and post-contrast), T2-weighted, and FLAIR MRI sequences for all subjects. Anatomical scans were defaced using PyDeface. Processed images include skull-stripped and MNI152-registered versions of each modality. Tumor segmentation masks were generated using the SegResNet CNN model following the BraTS labeling convention and subsequently reviewed / corrected by neuroradiologists.

Raw MRI data are provided for 337 patients, organized in BIDS folders labeled sub-***. 
Derivatives/processing/sub-*** includes preprocessed structural images, such as skull-stripped T1-WI, T2-WI, and FLAIR scans registered to the MNI152 standard space.
Derivatives/segmentation/sub-*** contains the tumor segmentation masks, which correspond spatially to the preprocessed images.

Molecular data, including MGMT promoter methylation status obtained via methylation-specific PCR, and demographic information for each participant are available in the "participants.tsv" file.

