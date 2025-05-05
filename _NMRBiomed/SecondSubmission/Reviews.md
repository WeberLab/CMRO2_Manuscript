We thank the reviewers for the helpful comments. We owe a strong apology to the reviewers for not uploading our Supplementary Materials that contained a large portion of the methods and equations. We have now moved that section back into the main document, and have uploaded the Supplementary Materials which contains a figure of our Hct prediction, and the STROBE checklist.

We have uploaded a Manuscript with tracked changes, and flagged which Reviewer comment we are addressing through the document. We have also uploaded a clean version of the Manuscript.

# Reviewer 1

> R1.1: This manuscript reports CMRO2 assessments in preterm neonates. The findings are clinically meaningful. However, CMRO2 or OEF algorithm from QSM is not clearly described.

We apologize for this. We included this information in the Supplementary Materials, although it mistakenly did not upload this document. However, we agree with the reviewer that this information should be included in the main text. We have now included this in the Methods under 'MRI data processing'. The calculation for CMRO~2~ and OEF are now equations 4 and 2, respectively.

> R1.2: The authors may consider the use of OEF mapping from QSM data as established in literature.

OEF mapping, as per PMID: 38247051 (Kudo et al. 2015) is very interesting. However, this method may be challenging in neonates, and may need to be validated in this population using PET. For example, Kudo et al. calculated CSvO~2~ by creating a venous mask within a 50 x 50 x 50 mm volume-of-interest and thresholding out values below +2 standard deviations within the volume. We are unsure if we would need to adjust these numbers, and have no way of validating our changes. However, we have included this technique in our Limitations as a point to consider for future researchers:

"CSvO~2~ values were not regional, but were averaged from the central cerebral veins. Future studies should look into ways of creating a regional voxel-by-voxel CSvO~2~ map. One source of inspiration could be Kudo et al. (2015), who created OEF maps from QSM data by using a local threshold method with a volume-of-interest (VOI) of 50 × 50 × 50 mm [@kudoOxygenExtractionFraction2016]. However, this would result in a low resolution image."

> R1.3: Results: "Mean whole-brain CSvO2, CSaO2, Hct and oxygen extraction fraction (OEF) values were": how were these values measured? I cannot find in the manuscript any description on CSaO2 and OEF measurements.

We apologize again for this. This information was originally in the Supplementary Materials but is now included in the Methods (see above). Calculation of CSvO~2~ can be found from Equation 1 now. CSaO~2~ was recorded from the pulse oximeter. We include this information in the Methods.

> R1.4: "D is simply B multiplied by a value determined by CSaO2, CSvO2, and Hct": how is the value determined – equation?

See above. We have now included a cross-reference to the equation in the figure caption.

> R1.5: Discussion: "measure the CSvO2 by averaging over all internal veins." "Our CSvO2 processing pipeline filtered out χ values below 0.15 ppm in order to obtain realistic values." These statements should be provided in methods to describe processing algorithm.

Thank you. This information is now included in the methods as per above. We sincerely apologize for including this in the Supplementary Material originally and for not uploading this document.

> R1.6: References: Cite recent consensus paper on QSM, PMID: 38247051; OEF mapping from QSM data: Kudo et al, PMID: 26661168; Cho et al, PMID: 29516537.

Thank you for taking the time to bring these to our attention. We have included these references throughout the manuscript.

# Reviewer 2

> R2.1: This study reported cerebral metabolic rate of oxygen (CMRO2) measurements in preterm neonates who underwent respiratory therapy. The authors quantified CMRO2 (and perfusion, venous oxygenation) values in these neonates and investigated their relationship to ventilation therapy duration and category. Given how challenging it is to measure CMRO2 in preterm neonates, this study is highly novel and provides some unique data to the literature. The manuscript was clearly written. The study is generally sound. My main comments are on the details of the methods, in particular the description of the SVO2 estimation and related results.

Thank you for your kind words and for taking the time to review our manuscript.

> R2.2: Methods: It would be useful to clarify whether the MRI scan was research-dedicated scan or clinical scan with research sequences added (clinical add-on).

Thank you. We now include a sentence stating that the MRI scans were completely research-dedicated:

"All scans were research-dedicated and not research sequences added on to clinical scans."

> R2.3: Methods: for pCASL imaging parameter, it’s unclear why 50 slices were acquired. 50 slices * 4mm = 200 mm. That will cover down to the shoulder of the neonate. Then where is the labeling plane. Please clarify. Also, "pulse label delay" should be "post-labeling delay".

The reviewer is correct. 50 slices is a typo. We acquired 25 slices at 4 mm. This information has been corrected. "Pulse label delay" has been changed to "Post-labeling delay".

> R2.4: Methods: SWI had a 1x1x2 mm3 voxel size. At this voxel size in neonates, if the venous ROI contains any tissue partial voluming. It would result in an over-estimation in venous oxygenation, or under-estimation in OEF and CMRO2.

The images were acquired at 1x1x2 mm^3^ but were reconstructed to 1x1x1 mm^3^ through zero-padded Fourier interpolation (ZIP2 on GE scanners). We acknowledge that this may introduce partial volume effects, particularly in small venous structures in neonates, where the voxels may contain a mixture of venous blood and surrounding tissue. We have added a note on this in the Limitations, and we appreciate the reviewer’s suggestion in highlighting this important consideration:

"Furthermore, our SWI sequence was acquired at 1 x 1 x 2 mm^2^ but were reconstructed to 1 x 1 x 1 mm^3^ through zero-padded Fourier interpolation. This interpolation may introduce partial volume effects, particularly in small venous structures in neonates."

> R2.5: Methods: The data processing for ASL, SVO2, and CMRO estimation were too brief. I could not find the supplemental file actually. In any way, these processing procedures should be included in the main text, as they are critical for the evaluation of the validity of the results.

We apologize. It appears we did not upload our Supplementary file when we submitted our main document. We have uploaded the file now, and have also moved the data processing information to the main text, as we agree they are critical for the evaluation of the validity of the results.

> R2.6: Methods: Related to the above comment, the authors should clarify whether the SVO2 result is a voxel-by-voxel map or a region of interest result. If ROI only, then how can one obtain a CMRO2 map. This is a bit puzzling.

We agree with the reviewer that, without the Supplementary material that is now included in the main text, the CSvO~2~ calculation is confusing. CSvO~2~ values were calculated from a vascular mask (this information now included in the methods) and were averaged. Thus, CSvO~2~ was not voxel-by-voxel like CBF values, but were an average of the central cerebral veins. CMRO~2~ maps use different CBF values per voxel, but the same CSvO~2~, CSaO~2~, and Hct values throughout. We apologize for this confusion, but believe that having the full methods now will make this less puzzling for future readers.

> R2.7: Results: In Figure 4, CMRO2 map is the same as the perfusion map. A single, global SVO2 value was used. Then how is the QSM based method better than the global SVO2 methods? Note that the results below talked about regional CMRO2. This is also confusing.

We apologize for the confusion. Our QSM method calculated CSvO~2~ values by averaging over the whole brain (excluding the SSS), while the previous CSvO~2~ methods averaged over only several voxels from a slice of the SSS. We originally wrote this in the discussion:
"Similarly, a strength of using QSM to study CSvO~2~ rather than previous MRI methods that used the TRUST [@liuQuantitativeAssessmentGlobal2014; @qiHemodynamicMetabolicAssessment2018] or T2-TRIR [@devisNoninvasiveMRIMeasurements2014], is that QSM produces a whole-brain map with high spatial resolution. By producing a whole-brain map, we were able to measure the CSvO~2~ by averaging over all internal veins. This is likely to produce a more robust measurement than acquiring a single slice and averaging within the superior sagittal sinus (SSS) as TRUST and T2-TRIR do. For the current study, our QSM maps were reconstructed to a 0.9 x 0.9 x 0.9 mm^3^ resolution, but future studies would benefit from acquiring and reconstructing up to 0.5 x 0.5 x 0.5 mm^3^. Indeed, greater spatial resolution would likely improve CSvO~2~ measurements as $\chi$ values could be better isolated to venous tissue without including non-venous sources. Finally, QSM could also allow for regional analysis of CSvO~2~ values, which we did not attempt here. Unfortunately, as our method for calculating QSM requires removing brain tissue along the edge of the brain (an eroded brain mask), we could not measure CSvO~2~ values in the SSS for more direct comparisons. Future work should be directed at acquiring QSM values in the SSS."

Regional CMRO~2~ refers to the fact that each voxel of our CMRO~2~ map is calculated by using a distinct CBF value, but global CSvO~2~, CSaO~2~, and Hct values. We agree that the way the manuscript was written is confusing, and have gone through and rewritten sections to make it clear that CSvO~2~ is also global, and that the regionality of our CMRO~2~ map derives from the ASL sequence. We believe that a lot of the confusion will be eliminated by including the full methods as opposed to referring to them in the Supplementary Materials.

We have also included this sentence in our limitations:

"CSvO~2~ values were not regional, but were averaged from the central cerebral veins. Future studies should look into ways of creating a regional voxel-by-voxel CSvO~2~ map. One source of inspiration could be Kudo et al. (2015), who created OEF maps from QSM data by using a local threshold method with a volume-of-interest (VOI) of 50 × 50 × 50 mm [@kudoOxygenExtractionFraction2016]. However, this would result in a low resolution image."
