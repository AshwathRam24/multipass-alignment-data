# Multipass amplifier data and code

Data, code and results for a study of alignment sensing in a Fourier-based multipass amplifier.

[Download the reproducibility archive](05_ESM_2_Reproducibility_Archive%20%285%29.zip?raw=true)

Extract the ZIP and follow the instructions in its `README.md`. It contains the digitized source data, analysis scripts, study notebook, stored results and figures.

The analyses use Python 3.10 or later. Install the dependencies in `requirements.txt`, then run the scripts in the order listed in the archive README.

The verification script checks 56 assertions against the result files. Run the analysis scripts first to verify newly computed results. Running the verifier alone checks the stored results.

The article uses the mechanical disk-tilt convention, `c_disk = 2`. The notebook includes earlier development outputs under a different convention. Those outputs are not the article's reported results.

The source data were digitized from figure 4 of Schuhmann et al., *Passive alignment stability and auto-alignment of multipass amplifiers based on Fourier transforms*, Applied Optics 58, 2904-2912 (2019), https://doi.org/10.1364/AO.58.002904.
