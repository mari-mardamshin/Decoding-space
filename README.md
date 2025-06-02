
# Decoding Space: Integrating Multiplexed Imaging and Deep Visual Proteomics  
**Material for the ASMS 2025 Bioinformatics Hub Workshop**  


## PIPΣX & MxDVP Hands-On Workshop  
This hands-on workshop replicates key steps in analyzing multiplexed tissue images and transitioning to single-cell deep proteomics:  
- Segmenting tissue cells and annotating markers using PIPEX  
- Exporting data for MS-based proteomics analysis  
- Performing QC and in-depth single-cell proteomics  
- Discussing challenges and opportunities in spatial-MS workflows  

⚠️ **Before the session:** Please complete the steps below to avoid delays and connectivity issues during the workshop!  

---

## 🔎 Before the Session  
**Install TissUUmaps**  
- Follow the [TissUUmaps installation guide](https://tissuumaps.github.io/installation/).  
- **Windows users:** Install version `3.2.1.11` as administrator.  

---

## 📝 Workshop Flow  
### 1️⃣ Short Introduction (10 min)  
- Why integrate multiplexed imaging with single-cell proteomics?  
- Challenges: data complexity, variability, QC, integration  

### 2️⃣ PIPEX Walkthrough (40–50 min)  
- Preprocessing for image quality  
- Membrane-aware segmentation and marker annotation  
- Export to TissUUmaps for exploration and to pyLMD for proteomics  
- Overview of segmentation, annotation, export, neighborhood analysis, and subtype discovery  

### 3️⃣ Single-Cell Proteomics Tutorial (40 min)  
- Preparing single-cell MS data  
- QC, normalization, rare subtype discovery  
- Directions of single-cell analysis (i.e. using scanpy or developing generalized pipeline for SCP)
- Single cell MS and spatial output data integration

### 4️⃣ Community Discussion (20–30 min)  
- Challenges in spatial-MS and multiomics integration  
- Tool sharing, collaborative ideas  
- Standardizing metadata and reference datasets  

### 5️⃣ Takeaways (2 min)  
- **MxDVP** enables reproducible, scalable analysis from images to single-cell proteomics.
- **Preprints to check for more information:** [Multiplexed Deep Visual Proteomics](https://www.biorxiv.org/content/10.1101/2025.04.27.650857v1), [PIPΣX](https://www.biorxiv.org/content/10.1101/2025.05.04.652145v1) 

---

## 🗂 Workshop Data  
- **Multiplexed Imaging (Mx):** Sample tissues from the Human Protein Atlas [source="HPA"](https://www.proteinatlas.org/about/licence) (link to be provided)  
- **Mass Spectrometry (MS):** Publicly available single-cell proteomics dataset [data availble from the Paper, 2023](https://pubmed.ncbi.nlm.nih.gov/37783884/)  

---

## 🔗 Resources Provided  
- **PIPEX + pyLMD repositories:** (link to be provided)  
- Sample datasets (`.tiff` images)  
- Annotated `.h5ad` example files  
- TissUUmaps integration  
- Workshop documentation  

---

## 🚀 Quick Start Checklist  
- [ ] Install TissUUmaps: [installation guide](https://tissuumaps.github.io/installation/)  
- [ ] Download the workshop data (link to be provided)
- [ ] Check [CellProfiling GitHub](https://github.com/CellProfiling) page for [PIPEX](https://github.com/CellProfiling/pipex)

---

## 🌸 Acknowledgments
We thank all contributors for their invaluable work on PIPΣX. Special thanks to Frederic Ballllosera Navarro, who led software development.

