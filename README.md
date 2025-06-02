
# Decoding Space: Integrating Multiplexed Imaging and Deep Visual Proteomics  
**Material for the ASMS 2025 Bioinformatics Hub Workshop**  


## PIPEX & MxDVP Hands-On Workshop  
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
- Export to TissUUmaps and pyLMD for proteomics  
- Overview of segmentation, annotation, export, neighborhood analysis, and subtype discovery  

### 3️⃣ Single-Cell Proteomics Tutorial (40 min)  
- Preparing single-cell MS data  
- QC, normalization, rare subtype discovery  
- Analysis with alphapeptstats and scanpy  

### 4️⃣ Community Discussion (20–30 min)  
- Challenges in spatial-MS integration  
- Tool sharing, collaborative ideas  
- Standardizing metadata and reference datasets  

### 5️⃣ Takeaways (2 min)  
- **MxDVP** enables reproducible, scalable analysis from images to single-cell proteomics  

---

## 🗂 Workshop Data  
- **Multiplexed Imaging (Mx):** Sample tissues from the Human Protein Atlas [source="HPA"](https://www.proteinatlas.org/) (link to be provided)  
- **Mass Spectrometry (MS):** Publicly available single-cell proteomics dataset (link to be provided)  

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
