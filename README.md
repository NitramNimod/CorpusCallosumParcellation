# Human Corpus Callosum Parcellation in MNI space

The Corpus Callosum (CC) is the largest white matter structure of the brain and offers the structural basis for an intense interaction between both cerebral hemispheres. Neuropathological processes are often reflected in structural alterations of the CC and a spatially precise description of structures for the healthy brain is essential for further differentiation of structural damage in patients.

This project is published under the CC BY-NC-SA 4.0 license (https://creativecommons.org/licenses/by-nc-sa/4.0/)

M1 motor cortex:

Based on the Brainnetome Atlas four major regions of the M1 were used as seed regions for probabilistic tractography of inter-hemispherical structural connectivity.<br>
The available NIFTI files can be found in "M1 - Motor cortex" and are organized as follows:<br>
A4hf - head/face movement region of the M1<br>
A4ll - lower limbs movement region of the M1<br>
A4tl - tongue/larynx movement region of the M1<br>
A4ul - upper limbs movement region of the M1<br>

For every callosal parcel different types exist:<br>
Four probability thresholds (0, 1%, 25%, 50%)<br>
Unmasked or multiplied by a binary mask of the Corpus Callosum.<br>

When using these regions in your scientific work, please cite:<br>
Parcellation of motor cortex-associated regions in the human corpus callosum on the basis of Human Connectome Project data<br>
DOI: 10.1007/s00429-019-01849-1

2022-03-16 New tracts added<br>
Again, based on the Brainnetome Atlas four available regions of the S1 were used as seed regions for probabilistic tractography of inter-hemispherical structural connectivity.<br>
The available NIFTI files can be found in "S1 - Sensory cortex" and are organized as follows:<br>
A1-2-3tonla - tongue/larynx sensory region of the S1 precentral gyrus<br>
A1-2-3tru   - trunk sensory region of the S1 precentral gyrus<br>
A1-2-3ulhf  - upper limbs/head/face sensory region of the S1 precentral gyrus<br>

For every callosal parcel different types exist:<br>
Four probability thresholds (0, 25%, 50%)<br>
Multiplied by a binary mask of the Corpus Callosum.<br>

Additionally, similar tracts were added, which are based on a task-related fMRI experiment involving real swallowing of a water bolus in chronic stroke patients mostly recovered from dysphagia and matched healthy participants.<br>
See this paper for details: Mihai, P. G., Otto, M., Domin, M., Platz, T., Hamdy, S., & Lotze, M. (2016). Brain imaging correlates of recovered swallowing after dysphagic stroke: A fMRI and DWI study. NeuroImage. Clinical, 12, 1013–1021. https://doi.org/10.1016/j.nicl.2016.05.006<br>
The available NIFTI files can be found in "S1 - Swallowing-related" and are organized as follows:<br>
Swallow_Postcentral_CC_only.nii.gz  - Tract derived from seeds which represent the BOLD activation of the sensory portion of swallowing function<br>
Swallow_Precentral_CC_only.nii.gz   - Tract derived from seeds which represent the BOLD activation of the motor portion of swallowing function
