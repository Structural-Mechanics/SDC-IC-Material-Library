# SDC-IC-Material-Library

The tool is an ANSYS APDL based script able to generate material properties characteristics, in SI units, for all the different materials (irradiated and unirradiated) contained in "SDC-IC In-vessel Components, Appendix A, Materials Design Limit Data, ITER_D_222RLN v3.2" 

#  SDC-IC-Material-Library Capabilities

  Definition of properties for the material model according "SDC-IC In-vessel Components, Appendix A".
  
  Definition of other properties according "SDC-IC In-vessel Components, Appendix A".

1. Definition of properties for the material model:

The properties for the material model are included in the material model that ANSYS use to describe the behavior of the material. These are:

    •	ALPX- Mean average or secant coefficient of thermal expansion
    •	CTEX- Instantaneous coefficient of thermal expansion
    •	EX- Young Modulus
    •	PRXY- Poisson's ratio
    •	DENS- Mass density
    •	KXX- Conductivity
    •	C- Specific heat
    •	MELAS- Stress-strain elastic curves. Nonlinear structural, multilinear elastic.
    •	BISO- Isotropic hardening plasticity. Bilinear stress-strain curves.
    •	MISO- Isotropic hardening plasticity. Multilinear stress-strain curves.
    •	BKIN- Kinematic hardening plasticity. Bilinear stress-strain curves.
    •	KINH- Kinematic hardening plasticity. Multilinear stress-strain curves.

2. Definition of other properties:

The so called “other” properties are properties not included in the material model but which may be used for post-processing tasks. These are:

    •	SY_MIN - Minimum yield strength
    •	SY_AV - Average yield strength
    •	SU_MIN - Minimum tensile strength
    •	SU_AV - Average tensile strength
    •	SY_IRR_MIN - Minimum yield strength. Material irradiated
    •	SY_IRR_AV - Average yield strength. Material irradiated
    •	SU_IRR_MIN - Minimum tensile strength. Material irradiated
    •	SU_IRR_AV - Average tensile strength. Material irradiated
    •	ETOT_MIN - Minimum total elongation
    •	ETOT_AV - Average total elongation
    •	EUNIF_MIN - Minimum uniform elongation
    •	EUNIF_AV - Average uniform elongation
    •	ETOT_IRR_MIN - Minimum total elongation. Material irradiated
    •	ETOT_IRR_AV - Average total elongation. Material irradiated
    •	EUNIF_IRR_MIN - Minimum uniform elongation. Material irradiated
    •	EUNIF_IRR_AV - Average uniform elongation. Material irradiated
    •	STRAIN_RUPT_MIN - Minimum true strain at rupture
    •	STRAIN_RUPT_AV - Average true strain at rupture
    •	SM - Allowable stress intensity
    •	SMB - Design stress intensity for bolt materials
    •	SE_IRR - Allowable stress for the primary plus secondary membrane stress intensity dependent on temperature and neutron fluence.
    •	FATIGUE_STRAIN - Fatigue curves for unirradiated material. Number of cycles - Strain amplitude (Strain/2). 
    •	FATIGUE_STRESS - Fatigue curves for unirradiated material. Number of cycles - Stress amplitude (Stress/2). 
    •	K_CYCL - Coefficient for cyclic stress - strain curves
    •	m - Coefficient for cyclic stress - strain curves
    •	K_v - Coefficient for cyclic stress - strain curves
    •	K_e - Coefficient for cyclic stress - strain curves

# License

Copyright 2019 F4E | European Joint Undertaking for ITER and the Development of Fusion Energy (‘Fusion for Energy’). Licensed under the EUPL, Version 1.1 or - as soon they will be approved by the European Commission - subsequent versions of the EUPL (the “Licence”). You may not use this work except in compliance with the Licence. You may obtain a copy of the Licence at: http://ec.europa.eu/idabc/eupl.html
Unless required by applicable law or agreed to in writing, software distributed under the Licence is distributed on an “AS IS” basis, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the Licence permissions and limitations under the Licence.
