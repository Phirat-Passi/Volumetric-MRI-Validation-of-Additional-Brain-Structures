# Volumetric MRI - Validation of Additional Brain Structures

Semantic segmentation for brain tumor analysis is a crucial application within the realm of computer vision, enabling early and precise diagnoses with heightened accuracy and safety. This advanced technique involves pixel-level classification, where each pixel in an image is assigned a label representing its corresponding object or feature. Particularly in tumor detection, semantic segmentation plays a pivotal role in identifying and distinguishing tumors from neighboring regions within the brain image, such as healthy tissue, edema, and necrotic regions. By harnessing deep learning architectures like U-NET and capitalizing on annotated datasets, semantic segmentation models become adept at recognizing tumors and precisely outlining their boundaries. This innovation holds transformative potential for revolutionizing the biomedical imaging domain, leading to more dependable and secure early patient diagnoses. The capacity to comprehend intricate brain tumor details on a micro level empowers healthcare systems with the acumen required for instantaneous decision-making, thereby ensuring patient well-being and fostering safer and more efficient patient care and diagnostics. This advancement is poised to significantly enhance patient care and diagnosis through a more nuanced understanding of brain tumor characteristics and their intricate interactions with surrounding anatomy, ultimately resulting in informed decision-making and tailored treatment strategies.

# Dataset: BraTS2020 (Training + Validation)

Source: https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation

BraTS (Multimodal Brain Tumor Segmentation) dataset is a widely used collection of medical imaging data obtained through MRI scans for brain                   imaging, each represented as NIfTI files (.nii.gz). These files are a common format for storing medical imaging data.

MRI Modalities Included:

1. T1 (T1-weighted):
   
        • Image Type: Native image.
        • Acquisition: Sagittal or axial 2D acquisitions.
        • Slice Thickness: 1–6 mm.

2. T1c (T1-weighted with Contrast Enhancement):
   
        • Image Type: Contrast-enhanced (Gadolinium) image.
        • Acquisition: 3D acquisition.
        • Voxel Size: 1 mm isotropic voxel size for most patients.

3. T2 (T2-weighted):
   
        • Image Type: T2-weighted image.
        • Acquisition: Axial 2D acquisition.
        • Slice Thickness: 2–6 mm.

4. FLAIR (T2-weighted FLAIR):

        • Image Type: T2-weighted FLAIR image.
        • Acquisition: Axial, coronal, or sagittal 2D acquisitions.
        • Slice Thickness: 2–6 mm

![image](https://github.com/Phirat-Passi/Volumetric-MRI-Validation-of-Additional-Brain-Structures/assets/67471222/6d2eaa26-637e-467e-90b1-f4eb1ce144df)

       Fig: Ratio of data used in training / testing / validation
