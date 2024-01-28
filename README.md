# minireport_Metabolomics_computational-biology-class-2024
Name : Mallika Naeklang 665070004-6
<br>Topic : What we do and what we learn from metabolomic class :book: 
:open_book:
<br> **Metabolomics** is systemic study of all the metabolites (<1000 Da) present within a biological system. This trems is different from **metabonomics** which is the quantitative measurement of metabolite thaht specific to the biological sample in the response to the stimuli
<br>
<br>
Metabolites are intermediates and end products of metabolism, and they can provide insights of the physiological state of an organism. Metabolomics aims to comprehensively profile and quantify these metabolites to understand metabolic pathways, biochemical interactions, and the overall metabolic phenotype of an organism under different conditions.
<br>
<br>
Metabolites :   1. Endogenous metabolite = small molecules naturally produced within an organism as part of its normal metabolic processes.<br>
2.Dietary component = small molecules (other organism metabolite) that is absorbed or ingested into an organism body.<br>
3. Microbial metabolite = mall molecules produced by microorganisms as part of their metabolic activities. <br>
4. Biofluid = small molecules found in bodily fluids such as blood, urine, saliva, cerebrospinal fluid, and others. These metabolites are produced as part of normal physiological processes.<br>
<br>
<br>***key methods and approaches to study metabolomics :***<br>
1. Mass Spectrometry (MS):  It separates metabolites based on their chemical properties using liquid or gas chromatography<br>
2. Nuclear Magnetic Resonance (NMR) Spectroscopy: on-destructive technique that provides structural information about metabolites based on their nuclear spins. It is particularly useful for identifying and quantifying metabolites in complex mixtures.<br>

<br>**NMR and data acquisition**
<br>*what is data acquisition?* <br>
During data acquisition, the sample is subjected to a series of RF pulses and the resulting NMR signals are detected by the RF coil. The signals are digitized and recorded as a function of time, frequency, or both, resulting in an NMR spectrum.
<br>
<br>
After data acquisition, the NMR spectrum is processed to remove noise, baseline correction, and phase correction. Advanced spectral analysis techniques, such as Fourier transformation and spectral deconvolution, are applied to extract structural and chemical information from the spectrum.
<br>
<br>
<br>**typical workflow of metabolic profiling**
<br>
1. Experimental Design and Sample Collection <br>
2. Sample Preparation <br>
3. Instrumental Analysis = using analytical techniques such as mass spectrometry (MS), nuclear magnetic resonance (NMR) spectroscopy, or chromatography-based methods (e.g., liquid chromatography, gas chromatography). <br>
4. Data Acquisition= get the raw data from the analytical instruments, including mass spectra, NMR spectra, or chromatograms.<br>
5. Data Preprocessing = remove noise, correct baseline drift, and normalize signal intensities, making a suitable format for downstream analysis<br>
6. Data Analysis <br>
7. Metabolite Annotation and Identification = detected metabolites by comparing experimental data with reference spectra, databases, and literature information. <br>
8. Interpretation and Validation = Interpret metabolic changes in the context of biological systems, pathways, and networks. Moreover, Validate key findings using independent sample sets or orthogonal analytical methods.<br>
<br>
<br>
### Preporcessing of the data <br>
*1.Phasing* =  adjusting the phase of the recorded NMR signal to ensure that it is consistent across the spectrum. 
<br>
<br>
you can adjust the shifting by using many software such as R studio<br>
```git add upload your NMR data file
git add Plot the NMR spectrum before phase correction
plot(nmr_data)
git add Perform phase correction (zero-order and first-order)
nmr_data_corrected <- phc(nmr_data)```
<br>
<br>


