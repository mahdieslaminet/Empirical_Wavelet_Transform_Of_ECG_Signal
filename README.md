# Empirical_Wavelet_Transform_Of_ECG_Signal
Empirical Wavelet Transform Of ECG Signal Example
Laucoma is one of the leading causes of vision loss.
This is caused due to the increased fluid pressure and
improper drainage of fluid in the eye [1]. It is estimated that
in 2013 worldwide 64.3 million aged 40 to 80 years suffered
from glaucoma. This figure is expected to reach 76 million
by 2020 and 111.8 million by 2040 [2]. The prevalence of
glaucoma is 2.5% for people of all ages and 4.8% for above
75 years of ages [3].
Diagnosis of glaucoma is mainly based on the Intra Ocular
Pressure (IOP), medical history of patient’s family [4], and
change in optic disc structure [5]. Glaucoma suspect will
have IOP more than 21 mmHg [6]. Other methods of mon-
itoring glaucoma involve Optical Nerve Hypoplasia Stereo
Photographs (ONHSPs), advanced imaging technology such
as Optical Coherence Tomography (OCT), Scanning Laser
Polarimetry (SLP), and Confocal Scanning Laser Ophthal-
moscopy (CSLO) to generate reference images to study the
eye and its internal structure [5]. These methods are expensive
and require skilled supervision. It is suggested that combin-
ing various imaging methods will significantly improve the
accuracy of glaucoma identification.
The glaucoma disease is characterized by change in the
structure of nerve fibers and optic disc parameters such as
diameter, volume, and area [5], [7]. Structural changes occur
due to obstruction to the discharge of aqueous humor, which
in turn increases IOP. This injures the optic nerve fiber
and prevents the transmission of information from eye to
the brain [8]. Ophthalmologists examine distinct regions to
identify disease during eye inspection. Different methods have
been employed to determine representative features such as
irregularity of blood vessels [9].
The fundus images are used for the diagnosis of glaucoma
[10], [11] and diabetic retinopathy [12]. Damage to optic nerve
fibre is detected using the morphological features of fundus
images [13]. Morphological features such as cup to disc ratio,
the ratio of area of blood vessels in inferior-superior side to
the nasal-temporal side, and ratio of distance between the optic
disc center and optic nerve head to diameter of the optic disc
are used to detect glaucoma [10]. In morphological methods,
choosing structural elements is difficult which may not yield
high classification accuracy [1], [10]. Image segmentation
based techniques have been used for glaucoma detection [10],
[14]. These segmentation have shortcomings like localization,
thresholding or demarcation which may lead to unacceptable
results and unavoidable errors in glaucoma diagnosis [1].
In order to overcome these difficulties, an automated diag-
nosis methods are preferred for glaucoma diagnosis. Selection
of robust features are necessary to develop a robust system.
Recent studies have shown that texture features [1], [15],
[16] are very effective for glaucoma image detection. Higher
Order Spectra (HOS) coupled with texture features are used
to improve the classification accuarcy [15]. In [16], Discrete
Wavelet Transform (DWT) energies are used as features for
glauoma detection. The HOS bispecturm features and wavelet
energy features are used for glaucoma diagnosis in [1]. Unlike
DWT, the Empirical Wavelet Transform (EWT) is a signal
dependent decomposition technique. The DWT has a set of
fixed basis functions that are signal independent. The working
principle of EWT depends upon frequency spectrum of the
signal. In this work, we are proposing a novel method for
the classification of glaucoma images based on EWT and
correntropy features. EWT decomposes the image into vari-
ous frequency bands. Correntropy [17] is extracted from the
decomposed EWT components. The features are normalized
