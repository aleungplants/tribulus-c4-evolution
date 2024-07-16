# Data for Leung et al. unpublished manuscript

NA in any data file indicates that the value was not determined. 

**aci_data.csv** and **cstar_aci_data.csv**: 
• TleafRounded: leaf temperature set points (30 or 42°C) such that data can be grouped in R
• Columns directly from LI6400XT output files

**crosssection_data.csv** (all areas in µm^2):
• AreaSection: total area of the leaf section within the view of the microscope
• AreaBSVein: total area of bundle sheath (BS) tissue + vascular tissue
• AreaVein: total area of vascular tissue
• AreaMesophyll: total mesophyll (M) tissue area 
• AreaBS: total BS tissue area

**‌cstar_data.csv**:
• Rd: respiration in the light
• Cstar: CO2 compensation point in the absence of respiration (C*)

**dot_data.csv** (all areas in µm^2; GDC indicates GLDH and GDCP indicates GLDP):
• GDC(P)DensityBS	and GDC(P)DensityM: colloidal gold particles / mitochondria area in BS and M tissues, respectively
• GDC(P)DensityBSCell	and GDC(P)DensityMCell: colloidal gold particles / cell area in BS and M tissues, respectively
•	GDC(P)DensityBSTissue and	GDC(P)DensityMTissue: colloidal gold particles across the leaf section in in BS and M tissues, respectively	
•	PercentGDC(P)inBSTissue: fraction of colloidal gold particles in the leaf section labelled in the BS tissues

**enzyme_data.csv**:
• RatePerLeafArea: enzyme activity per leaf area in µmol m^•2 s^•1
• Chl_umol_per_m2: chlorophyll concentration in µmol m^•2
• RatePerChl: enzyme activity per chlorophyll in mmol mol Chl^•1 s^•1

**gamma_data.csv**:
• Slope: initial slope of A/Ci curve (µmol m^•2 s^•1/µmol mol^•1 = mol m^•2 s^•1) 
• Gamma: CO2 compensation point of A/Ci curve (µmol mol^•1)

**organelle_data.csv**:
• Position: Regions of the BS cell; inner = centripetal; outer = centrifugal.	
• AreaCell: Area of the cell in µm^2
• AreaChloro and AreaMito: Area of chloroplasts and mitochondria in centripetal or centrifugal regions, µm^2
• nChloro and	nMito: Number of chloroplast and mitochondria
• AreaChloroTotal	and AreaMitoTotal: Totla area of organelles across whole cell
• AreaChloroPercent and	AreaMitoPercent: Fraction of organelle area in centripetal or centrifugal regions, %	
• AreaPerMito	and AreaPerChloro: Area of each organelle

**organelle_tissue_data.csv**:
• PercentMitoinBSTissue	and PercentChloroinBSTissue: Fraction of organelles allocated to the BS tissue, %

**paradermal_data.csv**
• Width, Length, and LWRatio: Bundle sheath length, width, and length•to•width ratio in µm


