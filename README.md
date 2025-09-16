# 📑 Clinical Data Pipeline with Quarto

## 📌 Abstract  

This repository hosts a **Quarto website** that documents the creation of a clinical data pipeline using synthetic HIV patient data. The project demonstrates the stepwise transformation of raw data into **standardized SDTM domains**, **analysis-ready ADaM datasets**, and **Tables, Listings, and Graphs (TLGs)** for clinical reporting.  

By leveraging R packages such as `dplyr`, `rtables`, and `ggplot2`, alongside reproducible documentation in Quarto, this project provides an educational example of how end-to-end clinical workflows can be structured, standardized, and visualized.  

## 👩‍💻 Author  

**Barbara Dalmaso, B.Sc. MBA, Ph.D.**  

## 🚀 Features  

- **End-to-end pipeline** from raw data to TLGs  
- **SDTM derivation** for core domains (`DM`, `MH`, `SC`, `EX`, `LB`)  
- **ADaM datasets** creation (`ADSL`, `ADLB`)  
- **TLGs generation** using `rtables` and `ggplot2`  
- **Fully reproducible Quarto website** for documentation and sharing  

## 🧰 Tools and Libraries  

### 📦 Installation and R packages  

```r
install.packages(c("dplyr", "rtables", "ggplot2", "haven", "quarto"))
```

- ```R``` version 4.3+
- ```dplyr``` – Data wrangling
- ```rtables``` – Clinical tables
- ```ggplot2``` – Graphical visualizations
- ```haven``` – Data import/export
- ```quarto``` – Reproducible documentation framework

### ▶️ Visit the Quarto Site
To render the documentation locally, clone this repo and run:
```bash
quarto render
quarto preview
```
Alternativelly, you can acess it at: https://barbaradalmaso.github.io/clinical-data-processing/ 

### 📜 License

This repository is intended for educational and academic use only.
All data is synthetic and does not represent real patient information.

### Enjoy :-)
