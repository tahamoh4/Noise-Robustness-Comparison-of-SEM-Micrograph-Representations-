# Noise Robustness of SEM Micrograph Representations Produced by Machine Learning and Statistical Methods

Jupyter notebook example of the code used to perform the noise robustness comparison of Segment Anything model (SAM), VAE, and 2 Point Statistical representations exposed to Gaussian, Poisson, blur, and S&P noise. The provided code performs procrustes analysis and single-image stability analysis via cosine similarity measurements on a micrograph dataset of interest.

## Data and Model Weight Availability
- SAM weights are governed by Meta's license and are not redistributed here. The SAM weights should be obtained directly from Meta's available resources. The weights for the domain-trained VAE are provided `SEM_VAE_Latent64_Beta0.2_20251223_1639.pth`
- Due to restrictions on the dataset employed in the study, a representative dataset of SEM micrographs is provided here for exploring noise robustness of the machine learning and statistical methods
- Python environment setup requirements are provided in `requirements.txt`
