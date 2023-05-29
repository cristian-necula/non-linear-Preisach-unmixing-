# non-linear-Preisach-unmixing-
Jupyter notebooks and data for non-linear Preisach measurements unmixing associated to "Resolving the Interpretation of Magnetic Coercivity Components from Isothermal Remanence Curves Using Unmixing of Non-linear Preisach Maps: Pedogenesis and Provenance in Loess-Paleosol Sequences" by Cristian Necula1, Ioan Lascu2, Cristian Panaiotu1, Daniela Gheorghe3


Data description

	1. Rerunnable jupyter notebooks:

Preisach_Lunca_unmixing.ipynb : perform Preisach data unmixing for Lunca section through SVD+ICA using Hyperspy (de la Pena et al., 2022) (used to reproduce Fig. 4) (this study)
Preisach_COS_unmixing.ipynb : perform Preisach data unmixing for Costinesti section through SVD+ICA using Hyperspy (de la Pena et al., 2022) (used to reproduce Fig. 5) (this study)

Lunca_IRM_fastica_unmixing.ipynb : perform coercivity distribution data unmixing for Lunca section through SVD+ICA using Hyperspy (de la Pena et al., 2022) (used to reproduce Fig. 6a, b) (this study)
COS_IRM_fastica_unmixing.ipynb : perform coercivity distribution data unmixing for Costinesti section through SVD+ICA using Hyperspy (de la Pena et al., 2022) (used to reproduce fig 6c, d) (this study)

Data: 

	2. Preisach data

L1_TM_P_mom_irm_norm.txt - L6_TM_P_mom_irm_norm.txt : normalized to 1 Preisach measurements for loess units from Lunca section (for Figs 3 and 4) (this study)
S0_TM_P_mom_irm_norm.txt - S6_TM_P_mom_irm_norm.txt : normalized to 1 Preisach measurements for paleosol units from Lunca section (for Figs 3 and 4) (this study)

L1_cos_mom_irm_norm.txt - L5_cos_mom_irm_norm.txt : normalized to 1 Preisach measurements for loess units from Costinesti section (for Figs 3 and 5) (this study)
S0_cos_mom_irm_norm.txt - S5_cos_mom_irm_norm.txt : normalized to 1 Preisach measurements for paleosol units from Costinesti section (for Figs 3 and 5) (this study)

COS-L1_NLP50steps_0.1-1000mT_3sec.csv : Preisach raw measurement for Costinesti L1 sample. It is used to get the applied fields for EMs Preisach maps calculation (Figs 4 and 5) 

COS_depth_Preisach.txt : depth (m) for selected Preisach samples from Costinesti. 
Lunca_depth_Preisach.txt : depth (m) for selected Preisach samples from Lunca


	3. IRM data:

Lunca_coercivity_dist.txt : interpolated 168 coercivity distributions for Lunca section (this study) (for Fig. 6a, b)

COS_coercivity_dist.txt : interpolated 131 coercivity distributions for Costinesti section (Necula et. al, 2015) (for Fig.6c, d)

field_TM_irm.txt : common nonlinear magnetic field on which the interpolation was done (mT) (for Fig. 6)

Lunca_IRM_acquisition_curves.txt : interpolated 168 IRM acquisition curves for Lunca section (Am^2/kg) (this study) (for Fig.2)

Lunca_depth_IRM.txt : depth (m) for selected coercivity distributions samples from Lunca section 

COS_depth_IRM.txt : depth (m) for selected coercivity distributions samples from Costinesti section



	4. Lunca granulometry data

Lunca_grano.txt : pedogenic (< 5 microns) fraction (column 2) (%) and airborne (> 16 microns) fraction (column 3) (%) versus depth (m) (first column) for Lunca section (for Fig. 2) (this study)

Lunca_MGS: Median grain size (microns) for Lunca section (Fig.8) (first column represents depth (m), second column represents MGS (microns)) (this study)

COS_MGS : Median grian size for Costinesti section (Fig.8) (first column represents depth (m), second column represents MGS (microns)) (this study)


	4. Lunca Magnetic susceptibility data

Lunca_klf: first column - depth (m) 

	second column - magnetic susceptibility measured for Lunca section (10 ^ -8 kg/m^3) (Constantin et al., 2015) (Fig.2)
