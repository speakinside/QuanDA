# QuanDA

Theoretical MALDI spectra of peptide before and after deamidation were essential for real sample analysis.
QuanDA is a method based on non-negative least squares for calculating the deamidation percentage in aging process of a standard peptide and therapeutic drugs.

## Files
The `QuanDA.ipynb` files gives an implementation and a usage example of the algorithm "QuanDA". Functions in `QuanDA.ipynb` have been annotated for reference.

The files in `data` directory is an example dataset. `data\D.txt` is the simulated spectra of the Pure Pep-D and `data\N.txt` is the simulated spectra of the Pure Pep-N. `data\Asn2Asp18` contains 10 measurements of sample composed of 10% Pep-N and 90% Pep-D, while `data\Asn18Asp2` contains 10 measurements of sample composed of 90% Pep-N and 10% Pep-D.

\* Pep-N and Pep-D are two synthetic peptides (Pep-N: YTHQGLSSPVTKSF**N**RGE and Pep-D: YTHQGLSSPVTKSF**D**RGE)