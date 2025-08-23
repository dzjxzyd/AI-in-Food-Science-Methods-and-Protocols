# Pretraining a Peptide Language Model from Scratch for Bioactive Peptide Discovery  

This repository contains the official code and protocols for the book chapter  
**“Pretraining a Peptide Language Model from Scratch for Bioactive Peptide Discovery”**  
in *AI in Food Science: Methods and Protocols*.  

The repository provides implementations for:  
- Pretraining the **PepBERT** peptide language model.  
- Downstream applications, including **quorum-sensing peptide prediction** using extracted embeddings.  

---

## Environment and System Setup  

All experiments in this protocol were conducted under the following environment:  

- **Operating System:** Linux-5.14.0-570.22.1.el9_6.x86_64 (glibc 2.34)  
- **Python:** 3.11.11  
- **PyTorch:** 2.6.0+cu124  
- **CUDA:** 12.4  
- **cuDNN:** 90100  
- **MPS availability:** False  
- **Device:** NVIDIA GPU (CUDA)  
