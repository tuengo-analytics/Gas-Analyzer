# Gas-Analyzer
Absorption Spectra Study

The purpose of this study is to conduct a search of optical absorption spectra of molecular gases in the region of near IR spectrum.
Examples of gas species to be detected are in the oil, natural gas industries.  Common gas species are: H2S, CO2, CH4, C2H6, etc.
The goal is to develop a cost-effective gas analyzer/detector to detect and measure gas concentration species in question.  
Each gas species has a unique signature in the absorption spectrum.  Usually these spectra span a wide range in the 
electromagnetic spectrum from far IR, mid IR, and near IR.  To develop a portable analyzer at low cost, 
solid state tunable diode lasers (TDL) are usually employed.  These TDL were made cost-effective due to their applications in
telecommunication.  They are typically operating in the near IR range.  So, the search in this study will limit in the near IR
region.  

The scope of this study is to search the absorption spectra for: H2S (toxic gas), CO2 and H2O vapor.  These gas species
have been found to have the absorption signature in the wavelength range of 1520 nm to 1550 nm.  

Raw data is query from the absorption database HITRAN: https://www.HITRAN.org
![](images/spectra.png)

The accompanied python notebook is to automate and screen the search of wavelength windows where all the gas species in question (H2S, CO2, and
H2O vapor in this case) have detectable level.  
The criteria are:

*The absorption wavelength of each gas species are well separated

*The relative absorption sensitivity among the gas molecules are comparable
