
# 🇫🇮 R – Finland Phillips Curve Analysis (Quarto)

This repository contains a Quarto (R) project that analyses the Phillips curve for Finland using macroeconomic time series data and standard econometric tools (unit root tests, cointegration and dynamic models). |  Este repositorio contiene un proyecto en Quarto (R) que analiza la curva de Phillips para Finlandia utilizando series temporales macroeconómicas y herramientas econométricas estándar (tests de raíz unitaria, cointegración y modelos dinámicos).

---

## 📄 Files / Archivos

- `Curva_phil_finland.qmd` – Main Quarto document with code, explanations and results.  
- `Curva_phil_finland_v2.pdf` – Rendered PDF version of the analysis.  

---

## 🔍 Main objectives / Objetivos principales

- Build and explore Finnish macroeconomic time series (inflation, unemployment, etc.) from international databases (World Bank).  
- Test for stationarity and unit roots and discuss implications for modelling.  
- Estimate Phillips curve‑type relationships and evaluate their fit and stability over time.

- Construir y explorar series temporales macroeconómicas de Finlandia (inflación, desempleo, etc.) a partir de bases de datos internacionales.   (Banco Mundial)
- Realizar tests de estacionariedad y raíz unitaria y discutir sus implicaciones para el modelado.  
- Estimar relaciones tipo curva de Phillips y evaluar su ajuste y estabilidad a lo largo del tiempo.

---

## 🛠️ R packages / Paquetes utilizados

The analysis uses a set of common R packages for time series and econometrics, including:

- `WDI`, `zoo` – data access and time series handling.  
- `ggplot2`, `ggfortify` – visualisation of series and model diagnostics.  
- `urca`, `fUnitRoots` – unit root and cointegration tests.  
- `lmtest`, `car`, `strucchange`, `dynlm` – regression diagnostics, structural breaks and dynamic modelling. 

El análisis utiliza un conjunto de paquetes habituales en R para series temporales y econometría, como son:

- `WDI`, `zoo` – acceso a datos y manejo de series temporales.  
- `ggplot2`, `ggfortify` – visualización de series y diagnósticos de modelos.  
- `urca`, `fUnitRoots` – tests de raíz unitaria y cointegración.  
- `lmtest`, `car`, `strucchange`, `dynlm` – contraste de modelos, rupturas estructurales y modelos dinámicos. 

---

## ▶️ How to run / Cómo ejecutar

1. Clone or download this repository. |  Clona o descarga este repositorio.  
2. Open `Curva_phil_finland.qmd` in RStudio (or another Quarto‑enabled editor). |  Abre `Curva_phil_finland.qmd` en RStudio (u otro editor compatible con Quarto). 
3. Ensure the required packages are installed (`install.packages(...)` as indicated in the document if needed).   |  Controla  tener instalados los paquetes necesarios (`install.packages(...)` según se indica en el documento si es preciso)
4. Render the document to your preferred format (HTML or PDF) using Quarto / RStudio.  |  Renderiza el documento al formato que prefieras (HTML o PDF) usando Quarto / RStudio.

---

## 👤 Author / Autor

Created by **JM Artiles** – Data Scientist & Economist‑in‑training.  


- GitHub: [JM-specialist-network](https://github.com/JM-specialist-network)  
- Email: joseartiles@g***l.com
