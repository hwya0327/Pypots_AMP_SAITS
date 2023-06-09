# Pypots_AMP_SAITS

- Pypots  
Wenjie Du. (2023). PyPOTS: A Python Toolbox for Data Mining on Partially-Observed Time Series.  
arXiv, abs/2305.18811. https://doi.org/10.48550/arXiv.2305.18811

- SAITS  
SAITS : Self-attention-based imputation for time series  
Wenjie Du, David Cote, and Yan Liu. SAITS: Self-Attention-based Imputation for Time Series.  
Expert Systems with Applications, 219:119619, 2023.

- AMP (Auto-Mixed Precision)  
Mixed Precision Training  
arXiv, 1710.03740. https://doi.org/10.48550/arXiv.1710.03740  

# Adoption
- base  
This file adopted AMP with Gradient scaling for training and validation process.  
Every imputation method provided from Pypots library would be applied.  

- grad_scaler  
This file changed for take parameters from optimizer.  

- module  
This file is a transformer module used for SAITS and transformer model.  
After adoption, overflow will not be happend.
