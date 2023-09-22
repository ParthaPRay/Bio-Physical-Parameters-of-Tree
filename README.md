# Bio-Physical-Parameters-of-Tree
This repo contains the infromation about various biophysiological parameters of a tree 

# Bio-Physical Parameters of a Tree

**1. Vapour-pressure deficit, or VPD**

It is the difference (deficit) between the amount of moisture in the air and how much moisture the air can hold when it is saturated. Once air becomes saturated, water will condense out to form clouds, dew or films of water over leaves. It is this last instance that makes VPD important for greenhouse regulation. If a film of water forms on a plant leaf, it becomes far more susceptible to rot. On the other hand, as the VPD increases, the plant needs to draw more water from its roots. In the case of cuttings, the plant may dry out and die. For this reason the ideal range for VPD in a greenhouse is from **0.45 kPa to 1.25 kPa**, ideally sitting at around 0.85 kPa. As a general rule, most plants grow well at VPDs of between 0.8 and 0.95 kPa.

To compute the VPD, we need the ambient (greenhouse) air temperature, the relative humidity and, if possible, the canopy air temperature. We must then compute the saturation pressure. Saturation pressure can be looked up in a psychrometric chart or derived from the Arrhenius equation. 

Formulation: https://en.wikipedia.org/wiki/Vapour-pressure_deficit

Basics of VPD: https://pulsegrow.com/blogs/learn/vpd


Formula to calculate VPD: VPD=(1− RH/100) × SVP(T)

Where,
RH = Relative Humidity (in percentage, e.g., 70 for 70%)
SVP(T) = Saturation Vapor Pressure at temperature T (in kPa). This can be approximated using the Tetens formula:

SVP(T)=0.6108 × e((17.27×T)/(T+237.3))
Here, 
T is the air temperature in degrees Celsius and 
e is the base of natural logarithm (approximately equal to 2.71828).


VPD = SPV(T) - AVP 
where, Actual Vapor Pressure (AVP) =  (RH x SVP(T))/100



Dew point temperature = Tdew = (237.3*X) / (17.269  ‐X)

where X = ln(Rh/100)+((17.269*Tair)/(237.3+Tair))
and
Tair is air temperature
Tdew is dew point temperature
and,
Vapor Pressure Deficit = es ‐ ea = es ‐ (Rh*es/100) at any instant



DEFINITIONS:
SATURATION VAPOR PRESSURE: water evaporating and condensing through the air‐water interface yields zero net transport.

Ideal gas law to sat vap pr: e = pRT

where,
e=vapor pressure in millibars

p=vapor density in mass/unit volume (g/cubic meter)

T=absolute temperature (degrees Kelvin)

R=vapor gas constant

If we use the universal gas constant for R, the formula becomes

e = 1.61pRT

which becomes

p = 0.622e/RT

This is known as VAPOR DENSITY or ABSOLUTE HUMIDITY of the atmosphere.

RELATIVE HUMIDITY is the ratio of the vapor density (or pressure) to the saturation vapor density (or pressure) at the same temperature.

APPROXIMATIONS:

For saturated vapor pressure in temperature range 25‐55 deg Fahrenheit:

e == 6.11 + 0.339(D‐32)

e = sat vap pr in millibars

D = dew point temperature in Fahrenheit

For saturated vapor pressure in temperature range 25‐55 deg Fahrenheit:

e == 0.18 + 0.01(D‐32)

e = sat vap pr in inches of mercury

D = dew point temperature in Fahrenheit

Relative humidity can be approximated from air and dew point by rh = 100 ((112 ‐ 0.1T + D) / 112 + 0.9T)**8

T = temperature

D = dew point
(Range of valid temperatures is unknown).

Dew point can be approximated in temp range ‐40 to 50 deg C by

T ‐ D = (14.55+0.114T)*x + ((2.5+0.007T)*x)**3 + ((15.9+0.117T)*x)**14

T = temperature

D = dewpt

x = complement of relative humidity in decimal form, ie. x = 1.0 ‐ (rh/100)











More formula links: 

**https://tc.copernicus.org/preprints/tc-2023-8/tc-2023-8.pdf**

_https://www.nasa.gov/centers/dryden/pdf/87878main_H-937.pdf_

_http://mc-computing.com/science_facts/Water_Vapor/Other_Formulas.html_

_https://journals.ametsoc.org/view/journals/apme/57/6/jamc-d-17-0334.1.xml_

_https://www.researchgate.net/profile/Junzeng-Xu/publication/257723701_Error_of_Saturation_Vapor_Pressure_Calculated_by_Different_Formulas_and_Its_Effect_on_Calculation_of_Reference_Evapotranspiration_in_High_Latitude_Cold_Region/links/542ddd6d0cf277d58e8e35fb/Error-of-Saturation-Vapor-Pressure-Calculated-by-Different-Formulas-and-Its-Effect-on-Calculation-of-Reference-Evapotranspiration-in-High-Latitude-Cold-Region.pdf?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIn19_

https://www.wikiwand.com/en/Vapour_pressure_of_water

https://pulsegrow.com/blogs/learn/vpd#:~:text=VPD%20%3D%20SVP%20%E2%80%93%20AVP&text=It's%20as%20simple%20as%20that.

https://andrewsforest.oregonstate.edu/data/studies/ms01/dewpt_vpd_calculations.pdf

https://www.omnicalculator.com/chemistry/vapour-pressure-of-water


**2. Bio-ristor**

References

https://www.mdpi.com/2227-9040/11/7/374

https://ieeexplore.ieee.org/iel7/6287639/10005208/10097476.pdf

https://link.springer.com/article/10.1007/s11119-023-10049-1

https://www.mdpi.com/2073-4425/14/6/1284

https://www.mdpi.com/1996-1944/16/5/1861

https://www.researchsquare.com/article/rs-2753352/latest.pdf



**3. Potential Evapotranspiration (PET)**



**4. Leaf Surface Resistance**


Reference: https://escomp.github.io/ctsm-docs/versions/master/html/tech_note/Photosynthesis/CLM50_Tech_Note_Photosynthesis.html


**5. Canopy Surface Temperature**



**6. Leaf Capacitance**

**7. Tree Tilt Monitoring**

**8. Leaf Area Index**


**9. Leaf Temperature**

*  Normalized Relative Conopy Temperature (NCRT) = (Tcanopy - Tmin) / (Tmax - Tmin)


**10. Chlorophyll Fluorescence**



**11. Leaf Spectrometry**

**12. Leaf Water Content**

**13. Light Extinction Coefficient**


Reference: https://link.springer.com/article/10.1007/s13580-011-0216-3

**14. Spectral Indices**

[https://github.com/ParthaPRay/AS7265x-Spectral-Indices](url)

* NDVI = (NIR - Red)/(NIR + Red)

* CNDVI = (NIR<sub>940</sub> - Red<sub>660</sub>)/(NIR<sub>940</sub> + Red<sub>660</sub>)

* WDVI = NIR - slope_soil * Red;
  
* PVI = (NIR - slope_soil × Red - intercept) / sqrt(slope_soil^2 + 1)
  
*  DVI = NIR - Red
  
*  TNDVI = sqrt((NIR - Red) / (NIR + Red) + 0.5)
  
*  EVI = 2.5 × ((NIR - Red) / (NIR + 6 × Red - 7.5 × Blue + 1))
  
*  SAVI = (1 + slope_soil) × (NIR - Red) / (NIR + Red + slope_soil)
  
*  GNDVI = (NIR - Green) / (NIR + Green)
  
*  TVI = 0.5 * (120 * (NIR - Green) - 200 * (Red - Green))
  
*  VARI = (Green - Red) / (Green + Red - Blue)
  
*  ExG = 2*Green - Red - Blue
  
*  ExR = 1.4*Red - Green
  
*  ExB = 1.4*Blue - Green
  
*  NGRDI = (Green - Red) / (Green + Red)
  
*  CIVE = 0.441Red - 0.811Green + 0.385*Blue + 18.78745
  
*  GLI = 2*Green - Red - Blue
  
*  CI = (NIR / Red) - 1

* CCI = ((NIR<sub>940</sub> / Red<sub>6600</sub>) - 1) / ((NIR<sub>940</sub> / Red<sub>660</sub>) + 1)

*  GCI = (NIR/Green) − 1
  
*  DGCI = (NIR - Green) / (NIR + Green)
  
*  PRI = (R531 - R570) / (R531 + R570)
  
*  RVI = NIR/Red
  
*  MNLI = (1 - 0.5) * ((1.08*(NIR-Red))/(1 + sqrt(NIR-Red)))
  
*  TCARI = 3 * ((Green-Red) - 0.2 * (Green-Blue) * (Green/Red))
  
*  MCARI = ((Red - Green) - 0.2 * (Red - Blue)) * (Red/Green)
  
*  RECI = (NIR/Red_edge) - 1
  
*  MSRI = ((NIR/Red) - 1) / (NIR/Blue)

* ARVI = (NIR - Red)/ (NIR + Red - 2* Blue)

* MSAVI = (1/2)* [2*(NIR+1) - Sqrt( (2*NIR+1)^2 - 8*(NIR -Red) )]

* Meris Terrestrial Chlorophyll Index  (MTCI) = (NIR -Red)/(Red- Blue)

* Normalized Difference Red-Edge Index (NDRE) = (NIR - RedEdge)/ (NIR + RedEdge)

* RENDVI = (NIR<sub>940</sub> - R<sub>710</sub>)/(NIR<sub>940</sub> + R<sub>710</sub>)     

* Simple Ratio Pigment Index (SRPI) = Red/Green

**Follwoing are difficult to measure by using AS7265x**



* OSAVI = (1.16 * (NIR<sub>840</sub> - R<sub>660</sub>)/(NIR<sub>840</sub> + R<sub>640</sub> + 0.16)     _...AS7265x NOT Possible_
* RDVI = (NIR<sub>840</sub> - R<sub>660</sub>)/(NIR<sub>840</sub> + R<sub>660</sub>)*(1/2)      _...AS7265x NOT Possible_
* SIPI = (NIR<sub>840</sub> - B<sub>450</sub>)/(NIR<sub>940</sub> + R<sub>660</sub>)    _...AS7265x NOT Possible_
* Anthocynanin Reflectance Index (ARI) = 1/R<sub>550</sub>) - 1/R<sub>700</sub>)     _...AS7265x NOT Possible_ 
* Caretenoid Reflectance Index (CRI) = 1/R<sub>510</sub>) - 1/R<sub>550</sub>)    _...AS7265x NOT Possible_
* Water Band Index (WBI) = R<sub>970</sub>)/R<sub>900</sub>)         _...AS7265x NOT Possible_


# GLCM

*  Grey Level Co-occurance Matrix (GLCM) contains Mean, Variance, Homogeneity, Contrast, Dissimilarity, Entropy, Second Moment, Correlation


# Various Parameters

* Various paramters of climate change:  Read Brun, P., Zimmermann, N.E., Hari, C., Pellissier, L., Karger, D.N. (preprint): Global climate-related predictors at kilometre resolution for the past and future. Earth Syst. Sci.     Data Discuss. https://doi.org/10.5194/essd-2022-212


# Calibration 

**1. Multivarite Claibration Techniques**

  * Partial least squares (PLS)
  * Support vector regression (SVR)
  * Least squares support vector machine regression (LSSVR)
  * Radial basis function (RBF) neural network (NN)

# Error Detection and Analysis

* PCA

* Standard error of calibration (SEC)
* Standard error of prediction (SEP)
* Bias
* R<sup>2</sup>
* MSE
* RMSE
* MAPE
* RPD
  

