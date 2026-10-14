# Classic-ColorChecker

Big Classic-ColorChecker
<img width="849" height="482" alt="image" src="https://github.com/user-attachments/assets/21dfc38b-0d77-4743-bbc9-aceaa0aabfbb" />

Small Classic-ColorChecker board 
<img width="1277" height="919" alt="image" src="https://github.com/user-attachments/assets/ee8f48fb-478c-41b0-8223-6223a3c42e79" />

### ColorChecker Spectral Reflectance Evaluation

We evaluate the spectral reconstruction accuracy of our system using a 24-patch ColorChecker. The figure compares the reconstructed reflectance spectra from two configurations (**Big** and **Small**) against ground-truth measurements.

**Ground-truth measurement.** To obtain ground-truth reflectance spectra, we illuminate the ColorChecker with a halogen light source (Thorlabs SLS201L) and measure the spectral response of each patch using a spectroradiometer (JETI specbos 1211-2). The measured spectra are normalized by a reference measurement of a Spectralon reflectance standard (Labsphere) acquired under the same illumination conditions.

**Spectral reconstruction comparison.** We reconstruct the reflectance spectra of all 24 ColorChecker patches using the Big and Small configurations and compare them with the measured ground truth. The plots show the reconstructed spectra over 400–1000 nm, together with the ground-truth measurements over their available wavelength range.

The **black solid lines** represent the Big configuration, the **blue solid lines** represent the Small configuration, and the **red dashed lines** indicate the measured ground truth. Each subplot corresponds to one ColorChecker patch, with wavelength (nm) on the horizontal axis and spectral reflectance on the vertical axis.


<img width="2389" height="1475" alt="image" src="https://github.com/user-attachments/assets/a43837cb-b7a8-46d5-8c47-8cafd1bd1a38" />
